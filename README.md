# TalkTrack: Monitor and Optimize Call Flows Effortlessly

## 📌 Project Overview

**TalkTrack** is a data warehousing and analytics project aimed at transforming raw customer interaction data (from call centers, chatbots, web logs, and emails) into actionable business insights. The project addresses limitations in traditional OLTP systems and proposes an OLAP-based data warehouse architecture to support complex querying, multi-dimensional reporting, and strategic analysis.

## 🧠 Objectives

- Improve visibility into call center performance
- Identify reasons behind customer dissatisfaction
- Analyze sentiment and call duration across channels
- Recommend strategies for agent training and self-service support

## 🏗️ Data Warehouse Architecture

- **Schema:** Star Schema with Fact Table + Dimension Tables
- **Fact Table:** Contains numeric data (e.g., call count, call duration, sentiment score)
- **Dimension Tables:** Include State, Issue Category, Channel, Agent, and Date
- **ETL Process:**
  - **Extract:** Pull data from OLTP systems (calls, chats, emails, web)
  - **Transform:** Clean, normalize, and standardize data
  - **Load:** Push into dimensional data warehouse

## 📊 Dashboards & Insights

Three key dashboards were built using **Power BI**:
1. **Home View:** Overview of total call performance, top issues, and KPI trends
2. **Grid View:** Real-time snapshot of billing issues, call durations, and regional trends
3. **Q&A View:** Business-driven answers to questions like:
   - Which states have the highest call volumes?
   - What issues are dominating customer service calls?
   - What’s the sentiment trend over time?

## 💡 Key Business Insights

- **Billing issues** are the top driver of negative sentiment.
- States like **California and Texas** require urgent service improvements.
- Performance gaps in **call duration and wait times** were identified.
- Enhancing **web/chatbot support** can reduce agent load.

## 🧰 Tools & Technologies

- Microsoft SQL Server (OLTP and OLAP support)
- Power BI (dashboard visualization)
- Excel (pre-processing and trend analysis)
- Data Modeling: Star Schema, Snowflake Schema
- ETL Processes (manual/automated staging)

## 👥 Team

- Sai Sanjay - [23030124191]
- Vedansh Arya - [23030124186]  
*BCA Students, Symbiosis Institute of Computer Studies & Research (SICSR), Pune*

## 📝 Conclusion

By leveraging data warehousing techniques and OLAP tools, this project successfully uncovered hidden insights in customer service operations and recommended targeted interventions to improve satisfaction, reduce handling times, and shift toward more efficient support channels.

---

