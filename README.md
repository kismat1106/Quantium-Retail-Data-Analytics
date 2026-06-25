# Quantium-Retail-Data-Analytics
A retail data analytics case study mapping customer segments and evaluating store trial layouts.
# Retail Data Analytics Case Study: Chips Category Performance

## 📌 Project Overview
This project simulates a real-world data analytics consultancy engagement for a major supermarket chain. Acting as a Data Analyst, the objective was to analyze customer transaction data, identify high-value purchasing behaviors, run experimentation (uplift testing) on store layouts, and deliver actionable insights to the Chips Category Manager.

* **Status:** Completed (June 2026)
* **Tools Used:** Python (Pandas, NumPy, Matplotlib, Seaborn) / R, MS Excel, PowerPoint
* **Skills Demonstrated:** Data Cleaning, Feature Engineering, Customer Segmentation, A/B Testing (Control-Trial Store Matching, t-tests), Commercial Communication.

---

## 🛠️ Task Breakdown & Methodology

### Task 1: Data Preparation & Customer Analytics
* **Objective:** Clean raw transaction and customer profile datasets and analyze purchasing behaviors to define the target customer segments.
* **Key Actions:**
  * Inspected data for anomalies; isolated and removed a major outlier (a commercial customer purchasing 200 packets of chips in a single transaction).
  * Enriched the dataset by extracting `PACK_SIZE` and `BRAND_NAME` using text parsing.
  * Segmented customers based on life stage and premium typology (e.g., Mainstream, Budget, Premium).
* **Key Insights:** 
  * *[Insert your specific finding, e.g., "Mainstream Young Singles/Couples drive the highest sales volume and prefer specific chip brands."]*

### Task 2: Experimentation and Uplift Testing
* **Objective:** Evaluate the performance of a new store layout trialed in Stores 77, 86, and 88.
* **Key Actions:**
  * Selected mathematically sound control stores using **Correlation** and **Manhattan Distance** metrics during the pre-trial period.
  * Conducted **independent t-tests** to compare trial store performance against control store performance during the trial period.
* **Key Insights:**
  The new layout resulted in a statistically significant increase in sales ($p < 0.05$) for Store 86, but showed mixed results in Store 77.

### Task 3: Analytics and Commercial Application
* **Objective:** Translate technical statistical findings into a high-level business recommendation deck for senior stakeholders.
* **Key Actions:**
  * Structured a professional presentation using the **Pyramid Principle** (delivering the core recommendation first, followed by supporting evidence).
  * Created clear data visualizations designed for non-technical managers.

---

## 📁 Repository Structure
* `/data`: (Optional/Mention if data is proprietary)
* `/scripts`: Jupyter Notebooks / R Markdown files containing data cleaning and statistical testing code.
* `/presentation`: The final executive summary presentation (PDF format).

---

## 🎓 Certification & Verification
This project was completed as part of the **Quantium Data Analytics Job Simulation** hosted on Forage.
* **Credential ID:** Enrolment Verification Code: 56WstkQjffbWTqBY6
* **Issued To:** Kismat Thapa
* **Date:** June 25th, 2026
Initial commit of project description
