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

## 🛠 **Technology Stack**
- **Elasticsearch:** For indexing and querying data.
- **Logstash:** Data ingestion pipeline.
- **Kibana:** Visualization and dashboard creation.

---

https://github.com/Lakshitbhattacharya/SDA-1_ELK_project/issues/1
