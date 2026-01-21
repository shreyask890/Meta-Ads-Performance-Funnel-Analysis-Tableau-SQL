# 📊 Meta Ad Performance & Conversion Analysis

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-blue?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-4B275F?style=for-the-badge)

## 📖 Project Overview

This project involves a **full-funnel analysis** of Meta (Facebook/Instagram) advertising campaigns to evaluate performance, optimize budget allocation, and identify audience trends. 

By analyzing over **200K impressions** and **25K clicks**, this dashboard provides actionable insights into the "leaky funnel" problem—where high engagement was not translating efficiently into purchases.

---

## 🎯 Business Problem

The marketing team observed high traffic but inconsistent ROI. The primary objective of this dashboard was to:

* **Analyze the Funnel:** Track the customer journey from `Impression` → `Click` → `Conversion`.
* **Optimize Ad Spend:** Identify which ad formats (Video vs. Static) and times of day yield the highest ROI.
* **Refine Targeting:** Pinpoint the most profitable demographic segments to improve the **0.61% Purchase Rate**.

---

## 📂 Dataset Structure

The analysis is based on four relational datasets modeled using a **Star Schema** approach:

* `ad_events.csv`: Transactional data containing timestamps, event types (Impressions, Clicks, Purchases), and platform details.
* `ads.csv`: Dimension table detailing ad types (Carousel, Video, Stories) and target interests.
* `campaigns.csv`: Budget allocation, start/end dates, and campaign duration.
* `users.csv`: Demographic data including age, gender, location, and interests.

---

## 🔑 Key Insights & Findings

Based on the data analysis, the following patterns emerged:

1.  **High Engagement, Low Conversion:** The campaigns achieved an exceptional **CTR of 11.76%** (industry avg ~1-2%), indicating strong creative appeal. However, the **Purchase Rate (0.61%)** highlights a need for landing page optimization.
2.  **Ad Format Performance:** **Video Ads** outperformed all other formats, delivering the highest Conversion Rate (**5.2%**) and Engagement Rate (**13.7%**).
3.  **Demographic Targeting:** The **Female 18-30** age group showed the highest engagement, particularly in markets like **India and Brazil**.
4.  **Optimal Timing:** Engagement peaks during **afternoon and evening hours**, suggesting a need for day-parting strategies (scheduling ads for specific hours).

---

## 📊 Dashboard Visuals

> *Note: Click the images below to view the interactive dashboard on Tableau Public.*

![Dashboard Screenshot 1](link_to_your_image_here)

* **KPI Cards:** Tracking Total Impressions (216K), Spend ($2.5M), and CTR.
* **Funnel Analysis:** Visualizing the drop-off from Awareness to Purchase.
* **Donut Charts:** Breaking down engagement by Gender and Device.
* **Dual Axis Charts:** Correlating Ad Spend vs. Returns over time.

---

## 🛠 Tools Used

* **Tableau:** For data visualization, calculated fields, and interactive dashboard creation.
* **Data Modeling:** Star schema implementation joining Fact tables (Events) with Dimension tables (Users, Ads).
* **Statistical Analysis:** Calculation of custom metrics like CPC (Cost Per Click), CTR (Click-Through Rate), and CPM.

---

## 🚀 How to Run

1.  **Clone this repository:**
    ```bash
    git clone [https://github.com/yourusername/meta-ads-analysis.git](https://github.com/yourusername/meta-ads-analysis.git)
    ```
2.  **Open the file:**
    Open the `.twbx` file in **Tableau Public** or **Tableau Desktop**.
3.  **Connect Data:**
    Ensure the data source connection points to the `data/` folder included in this repo if not embedded.

---

### 👤 Author

**[Your Name]** [LinkedIn](Your_LinkedIn_URL) | [Portfolio](Your_Portfolio_URL)
