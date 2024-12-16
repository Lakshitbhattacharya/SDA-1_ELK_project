# 🚀 **ELK Sales Analysis Dashboard**
This project features an **interactive dashboard** built using the **ELK (Elasticsearch, Logstash, Kibana)** stack. The goal is to analyze **product sales trends, stock movements, and customer distributions** to derive actionable insights for a business.

---

## 📊 **Key Features**
1. **Top 10 Sold Products:**  
   A bar chart showing the most sold products based on median quantity.
2. **Country-Wise Sales Insights:**  
   - *Top 5 countries* contributing to sales.  
   - Customer distribution visualized in a pie chart.
3. **Revenue Contribution per Country:**  
   A breakdown of revenue generation by region, highlighting key markets.
4. **Stock Movement Analysis:**  
   Insights into stock quantities for key invoices.
5. **Price Distribution of Products:**  
   Visualizing product prices to identify high-value contributors.
6. **Sales Frequency Analysis:**  
   A time-series graph showing product sales over time intervals.

---

## 🔍 **Questions Answered by the Dashboard**
This project answers:
1. *Which products sell the most?*  
2. *Which countries contribute the most to sales?*  
3. *What percentage of sales come from each region?*  
4. *What is the price distribution across products?*  
5. *How frequently are products being sold?*  
6. *What does stock movement look like for the top invoices?*  
7. *Where can revenue be improved geographically?*

---

## 📈 **Recommendations Based on Insights**
1. **Focus on High-Performing Products:**  
   - Products like *“fairy_tale_cottage_nightlight”* dominate sales; consider promotional campaigns or bundling.
2. **Regional Strategy Optimization:**  
   - The **United Kingdom** contributes ~91.43% of customers and ~55.17% of revenue. Expand outreach to underperforming regions like *Eire* and *France*.
3. **Monitor Stock Movement:**  
   - Regular stock checks are essential to avoid product unavailability for top invoices. Consider inventory alerts.
4. **Revenue Diversification:**  
   - Strengthen the product line in high-potential regions like **Norway** (11.49%).

---

## ⚙️ **Setup Instructions**
1. **Pre-requisites:**
   - ELK Stack installed and running.
   - Data loaded into Elasticsearch.
   - Kibana for visualization.

2. **Clone this Repository:**
   ```bash
   git clone https://github.com/yourusername/elk-dashboard-sales-analysis.git
   cd elk-dashboard-sales-analysis
   ```

3. **Configure Data Pipelines:**
   - Set up **Logstash** pipelines to ingest sales data.

4. **Import the Dashboard:**
   - Navigate to Kibana → Dashboard → Import JSON (if provided).

5. **Run and Analyze:**
   - Launch Kibana and explore visualizations.

---
[Screencast from 16-12-24 06_21_55 PM IST.webm](https://github.com/user-attachments/assets/b580ce11-8ef0-42f6-8e58-c1a0b6534524)
---

## 🛠 **Technology Stack**
- **Elasticsearch:** For indexing and querying data.
- **Logstash:** Data ingestion pipeline.
- **Kibana:** Visualization and dashboard creation.

---

![Screenshot from 2024-12-16 18-21-31](https://github.com/user-attachments/assets/9fa038e1-28f9-401c-bdfe-0c9dc243c3e5)
![Screenshot from 2024-12-16 18-23-00](https://github.com/user-attachments/assets/227e7d5e-fd99-44b0-83e0-69e0b97cbdf0)
![Screenshot from 2024-12-16 18-23-11](https://github.com/user-attachments/assets/ca659299-1ef4-4d06-977f-35e42b2e7f0c)
![Screenshot from 2024-12-16 18-23-21](https://github.com/user-attachments/assets/da859f13-016d-46fa-a8e1-ffb769fb5298)
