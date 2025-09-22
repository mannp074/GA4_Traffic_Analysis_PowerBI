# Website Traffic & Engagement Analysis (Google Analytics 4)

## 1. Overview

This project simulates a real-world business analyst scenario for an e-commerce company. The primary challenge was to take raw, complex Google Analytics 4 (GA4) data from BigQuery and transform it into an actionable, two-page Power BI dashboard. As the Business Analyst, my role was to clean the data, identify key performance indicators (KPIs), and translate analytical findings into strategic recommendations for stakeholders. This entire process was enhanced by using an AI co-pilot (Google Gemini) to accelerate the data modeling, DAX generation, and insight discovery workflow.

---

## 2. Dataset

* **Source:** Google Analytics Sample Dataset for GA4
* **Description:** This public dataset contains obfuscated GA4 data from the Google Merchandise Store. It includes millions of events, each with nested parameters detailing user interactions, traffic sources, device information, and geographical data. The data was sourced directly from Google's BigQuery cloud data warehouse.

---

## 3. Methodology (STAR Framework)

This project followed the STAR framework to address the core business problem.

* **Situation:** An e-commerce company needed to understand its website traffic patterns to make data-driven decisions, but the raw GA4 data was too complex for direct analysis by stakeholders.

* **Task:** My objective was to process and model the raw data to build an interactive Power BI dashboard. This dashboard needed to clearly answer stakeholder questions about channel performance, user engagement, and popular content.

* **Action:**
    1.  **Data Cleaning (ETL):** I engineered a data pipeline in Power Query to handle the complex, nested JSON structure of the GA4 data. This involved parsing records, pivoting key-value pairs, and creating custom conditional columns (e.g., `Channel Grouping`) to make the data business-friendly.
    2.  **Dashboard Development:** I designed and built a two-page Power BI dashboard with a focus on usability and clear storytelling.
    3.  **Insight Generation:** I analyzed the completed visuals to identify trends, anomalies, and opportunities.

* **Result:** The final dashboard provided clear, actionable insights that enabled data-driven recommendations for the business.

---

## 4. Power BI Dashboards

The final report consists of two dedicated dashboards for different analytical purposes.

**[Link to your Live Interactive Dashboard on Power BI Service]**

### Dashboard 1: Traffic Acquisition Overview
This dashboard answers the question: **"Where are our users coming from and how effective are our marketing channels?"** It provides a high-level summary for executives and marketing managers.

*[Insert Screenshot of your Traffic Acquisition Dashboard here from the `assets` folder]*

### Dashboard 2: User Engagement Analysis
This dashboard answers the question: **"What are users doing on our site and how does their behavior differ across platforms?"** It provides deeper insights for product and content teams.

*[Insert Screenshot of your User Engagement Dashboard here from the `assets` folder]*

---

## 5. Insights & Business Recommendations

The analysis yielded three key business recommendations:

1.  **Finding:** Organic Search is the dominant user acquisition channel.
    * **Recommendation:** Double down on SEO investment to capitalize on this existing strength and further grow the primary traffic source.

2.  **Finding:** Mobile users are significantly less engaged than desktop users, despite representing a large portion of traffic.
    * **Recommendation:** Initiate a comprehensive UX/UI audit for the mobile website to identify and remove friction points in the user journey.

3.  **Finding:** Data collection for tablet users is incomplete, showing engagement time but no page-specific data.
    * **Recommendation:** Launch a technical investigation into the data collection pipeline for tablet devices to fix this analytics blind spot.

---

## 6. Skills Demonstrated

* **BI & Visualization:** Power BI, Dashboard Design, Data Storytelling
* **Data Transformation (ETL):** Power Query, Data Cleaning, Data Modeling, JSON Parsing
* **Data Sourcing:** Google BigQuery
* **Business Acumen:** Stakeholder-Focused Analysis, KPI Identification, Actionable Recommendations
* **Modern Workflow:** AI-Assisted Analysis & Code Generation (with Google Gemini)
