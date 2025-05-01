# BIBA
This project presents a data-driven solution to address delivery inefficiencies and customer churn in Yippee, a fictional FMCG company.


# 🚀 Leveraging BI & CRM to Improve Delivery Performance and Customer Retention for Yippee in the FMCG Sector

## 📘 Overview

This project presents a data-driven solution to address delivery inefficiencies and customer churn in Yippee, a fictional FMCG company. By integrating Business Intelligence (BI) tools and Customer Relationship Management (CRM) systems, the project aims to improve delivery performance, enhance customer satisfaction, and retain high-value clients.

---

## 📊 Key Objectives

- Analyze supply chain and delivery data to detect operational bottlenecks.
- Track delivery performance using real-time Power BI dashboards.
- Integrate CRM (e.g., Salesforce) for customer feedback capture and proactive resolution.
- Reduce customer churn by identifying and addressing root causes of dissatisfaction.
- Enhance business stability and prepare for expansion into Tier 2/3 cities in India.

---

## 🏗️ System Architecture

The solution consists of:
- **Mock Dataset Generation** using Python and Faker.
- **Data Preprocessing & EDA** using Pandas and Matplotlib.
- **Power BI Dashboards** for OTIF (On-Time, In-Full) delivery performance, customer satisfaction, and supply chain bottlenecks.
- **Salesforce CRM Configuration** with automated feedback loops and alerts.

---

## 🧾 Dataset Structure

| Table           | Description |
|----------------|-------------|
| `Customer`      | Contains customer type, region, and identifiers. |
| `Product`       | Product name, weight. |
| `Order`         | Order date, quantity, customer ID. |
| `OrderProduct`  | M:N link between orders and products. |
| `Delivery`      | Delivery status, delay, flood impact, warehouse info. |
| `Feedback`      | Satisfaction score, complaint type, contract renewal status. |

---

## 🧪 Notebooks

### 📁 `mock_data_Code.ipynb`
- Generates mock data using the `Faker` library.
- Ensures referential integrity and realistic business logic.

### 📁 `Data Preprocessing & EDA_Code.ipynb`
- Performs data cleaning and transformations.
- Generates summary statistics and visualizations to uncover patterns and issues in the delivery pipeline.

---

## 📈 Power BI Dashboards

Three dashboards were built:

1. **Delivery Performance Dashboard**  
   - OTIF trends, delay analysis, and regional performance.
2. **Customer Satisfaction & Retention Dashboard**  
   - Complaint types, satisfaction score, churn risk.
3. **Supply Chain Bottlenecks Dashboard**  
   - Warehouse inefficiencies, flood impacts, delay trends.

---

## 🛠️ CRM Configuration

Built in **Salesforce**, includes:
- Custom objects and fields for deliveries and complaints.
- Automated alerts and flows (e.g., flagging partial deliveries).
- Record types and page layouts for Retail vs Wholesale customers.

---

## 🔍 Key Insights

- Mid-sized warehouses are overutilized and flood-sensitive.
- Regional disparities in delivery performance.
- CRM data enhances visibility into at-risk customers and churn patterns.
- Real-time dashboards empower proactive intervention.

---

## 🔗 Important Links

- 📊 [Power BI Dashboards Preview (Video)](https://youtu.be/ed6qfLRfBtM)  
- 💡 [Supply Chain Dataset on Kaggle](https://www.kaggle.com/datasets/samwash94/supply-chain-optimization-for-yippee/data)  
- 🧠 [Miro Team Collaboration Board](https://miro.com/app/board/uXjVIDtanEY=/?share_link_id=148272029193)

---

## 👥 Contributors

- Shivansh Bhatnagar (x23237252)  
- Malav Naik (x23271779)  
- Pratik Sunar (x23292512)  

---

## 📅 Submission Info

- **Course:** MSc in Data Analytics  
- **Module:** Business Intelligence & Business Analytics  
- **Instructor:** Sean Heeney  
- **Submitted on:** 14 April 2025

---

## 📄 License

This project is for academic purposes. All data used is either mock-generated or open source (Kaggle). Please reference accordingly.