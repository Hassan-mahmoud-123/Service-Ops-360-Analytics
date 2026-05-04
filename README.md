# 🛠️ Service-Ops 360: Operational Excellence & Workforce Intelligence

## 🌟 Overview
This project transforms fragmented service operations data into a high-performance **360-degree Analytical Engine**. Beyond just visualization, this solution focuses on **Resource Optimization** and **Contractual Compliance** for a large-scale service enterprise.

---

## 🏗️ Data Architecture & Strategic Modeling
The core strength of this project is the **Custom-Built Star Schema**. 
- **Strategic Linking:** Instead of following basic relationships, I engineered the Data Model based on **Business Questions**. Every relationship was created to enable specific cross-functional insights between Workforce, Contracts, and Customer Satisfaction.
- **Feature Engineering (Power Query):** 
  - Conducted extensive data cleaning on raw Excel sheets.
  - Developed custom columns to track **Labor Coverage Gaps** and **SLA Penalties**.
  - Structured the `Staff Assignment` fact table (64K+ records) to seamlessly interact with geographical and temporal dimensions.

---

## 📊 Key Insights & Business Logic
Through this dashboard, I’ve unlocked critical operational metrics:
- **Labor Capacity vs. Requirements:** Identified a **156.33% Coverage Ratio**, indicating potential over-staffing or inefficient allocation in specific shifts.
- **Contract Health Tracking:** Automated the monitoring of **670 Active Contracts**, with real-time alerts for 127 contracts nearing expiration.
- **SLA & Quality Control:** Correlated 655 complaints with specific contracts and sites to identify root causes of service failure.
- **Geographical Footprint:** A spatial analysis of services across Egypt to optimize logistical support for field representatives.

---

## 🛠️ Tech Stack
- **Engine:** Power BI Desktop
- **ETL/Feature Engineering:** Power Query (M-Language)
- **Modeling:** Advanced Star Schema (optimized for high-volume transactions)
- **Analytics:** DAX (Time Intelligence & Dynamic Operational Measures)

---

## 📁 Project Structure
- `Services_Company.xlsx`: The cleaned and structured dataset.
- `Service_Ops_Analysis.pbix`: The final Power BI file with the optimized Data Model.
- `Screenshots/`: Visual gallery of the Model, Executive Overview, and Geographical Map.

---

## 💡 Why This Project?
It demonstrates the ability to handle **complex business logic** where data isn't just "connected"—it's **architected** to drive decision-making. By bridging the gap between Workforce Management and Financial Performance, this tool acts as a "Control Room" for the entire operation.
