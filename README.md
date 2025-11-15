

---

## **Bellabeat Case Study – Data Analysis & Marketing Insights**

**Author:** Meaad Farag Awadh Bayuosef
**Date:** November 2025
**Tools:** R (tidyverse, ggplot2, lme4), Excel Power Query
**Project Type:** Data Cleaning, Exploratory Analysis, Segmentation, Marketing Insights

---

### **Overview**

This project analyzes Fitbit smart device data to uncover behavioral patterns and extract marketing insights for **Bellabeat**, a wellness technology company focused on women’s health.
The analysis follows the **Google Data Analytics Capstone (Bellabeat Case Study)** framework, using R and Excel for data cleaning, transformation, visualization, and business interpretation.

---

### **Objectives**

* Identify trends in daily activity, calories, and sleep data from Fitbit users.
* Understand which metrics best represent user engagement.
* Segment users by activity levels and propose personalized marketing actions.
* Translate data findings into **practical, data-driven marketing recommendations**.

---

### **Data Sources**

* **FitBit Fitness Tracker Data_original data before cleaning.xlsx** → Raw dataset from Kaggle (30 users).
* **Cleaned_Bellabeat_Data_Final.xlsx** → Merged and cleaned dataset used for analysis.

  * Standardized timestamps, removed non-wear days (`steps < 1000`), unified variable names.

---

### **Data Cleaning Process**

Performed using **Excel Power Query** and **R scripts**:

1. Merged daily, hourly, and minute-level datasets.
2. Removed duplicates, formatted timestamps, filtered incomplete logs.
3. Created derived variables: total active minutes, day of week, weekend flag, etc.
4. Exported cleaned dataset for exploratory and statistical analysis.

---

### **Analysis Summary**

Conducted in R using the file `Bellabeat_CaseStudy_RMarkdown.Rmd`

* **Correlation Analysis:**

  * Steps vs Very Active Minutes (r ≈ 0.69) → strongest link.
  * Steps vs Calories (r ≈ 0.50).
* **Segmentation (k=3):**

  * Low, Medium, and High activity groups based on total steps and active minutes.
* **Time Pattern Analysis:**

  * Peak activity around **12 PM** and **6–7 PM** (best for app notifications).
* **Weekday vs Weekend:**

  * No major difference in mean daily steps.
* **Sleep Relation:**

  * Weak correlation with daily activity (r ≈ -0.17).

---

### **Key Marketing Insights**

1. **Primary engagement metric:** Very Active Minutes.
2. **User segmentation:**

   * *Low activity:* daily challenges and motivation.
   * *Medium activity:* gamified progress badges.
   * *High activity:* upsell premium devices or coaching plans.
3. **Notification timing:** Send push messages during 12 PM and 6–7 PM.
4. **Dashboard recommendation:** Track active minutes, segment retention, and campaign lift.

---

### **Repository Structure**

```
Bellabeat_Case_Study/
│
├── Bellabeat Case Study Report.docx            # Full written report
├── Bellabeat Case Study.pptx                   # Presentation slides
├── Bellabeat_CaseStudy_RMarkdown.Rmd           # R Markdown analysis script
├── Bellabeat_CaseStudy_RMarkdown.html          # Rendered HTML output
│
├── Cleaned_Bellabeat_Data_Final.xlsx           # Final cleaned dataset
├── FitBit Fitness Tracker Data_original data befor cleaning .xlsx # Raw data
│
├── outputs/                                    # Intermediate results
│   ├── correlations_steps_metrics.csv
│   ├── daily_filtered_steps1000.csv
│   ├── segment_summary_k3.csv
│   ├── recommendations.txt
│   └── ... (other derived data files)
│
└── plots/                                      # Visualizations & charts
    ├── steps_vs_active_minutes.png
    ├── steps_vs_calories_filtered_v2.png
    ├── avg_steps_by_hour.png
    ├── violin_total_steps_weekday_vs_weekend.png
    └── ... (19 visualization images)
```

---

### **Key Deliverables**

| File                                 | Description                                        |
| ------------------------------------ | -------------------------------------------------- |
| `Bellabeat_CaseStudy_RMarkdown.Rmd`  | Core R script used for cleaning and analysis       |
| `Bellabeat_CaseStudy_RMarkdown.html` | Final analytical report (visual + code)            |
| `Bellabeat Case Study Report.docx`   | Full written case report                           |
| `Bellabeat Case Study.pptx`          | Presentation slides summarizing findings           |
| `Cleaned_Bellabeat_Data_Final.xlsx`  | Final processed dataset                            |
| `/outputs`                           | Supporting intermediate data files                 |
| `/plots`                             | Visualization outputs for reports and presentation |

---

###  **Results Summary**

* The most reliable indicator of engagement is **Very Active Minutes**.
* Activity levels are consistent across weekdays and weekends.
* Data supports **personalized push strategies** based on user segment and activity hour.
* Findings directly inform Bellabeat’s marketing campaigns.

---

###  **Contact**

For portfolio or collaboration inquiries:
**Author:** Meaad Farag Awadh Bayuosef
**Field:** Data Analytics & Machine Learning
**Tools:** R, Python, Excel, Power BI

---

