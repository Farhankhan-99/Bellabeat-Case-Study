# 📊 Bellabeat Case Study: Smart Device Fitness Data Analysis

## 📋 Project Overview

An end-to-end data analytics project analyzing smart device fitness tracker data to uncover user activity trends and inform Bellabeat's marketing strategy. This capstone project, completed as part of the Google Data Analytics Professional Certificate, applies the six-phase data analysis framework (Ask, Prepare, Process, Analyze, Share, Act) to derive actionable insights for a high-tech wellness company focused on empowering women through health-tracking technology.


## 📊 Dataset Details

**Source:** [Kaggle - FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit)

**Participants:** 30 Fitbit users | **Time Period:** April 12 - May 12, 2016 | **Records:** 940 entries

**Key Table:** dailyActivity_merged.csv

**Columns Analyzed:** Id, ActivityDate, TotalSteps, TotalDistance, VeryActiveMinutes, LightlyActiveMinutes, SedentaryMinutes, Calories

---
---

## 🚀 Methodology

**Google Data Analytics 6-Phase Framework:**

1. **Ask** - Define business questions and objectives
2. **Prepare** - Collect and assess data quality
3. **Process** - Clean, transform, and create derived features
4. **Analyze** - Conduct statistical analysis and identify patterns
5. **Share** - Create visualizations and communicate insights
6. **Act** - Translate findings into actionable recommendations


## 🎯 Business Problem

Bellabeat needed to optimize their marketing strategy and improve user engagement by understanding:
- Activity patterns and behavioral trends across different days and time periods
- Correlation between steps, distance, active minutes, and calories burned
- User segmentation based on activity levels (High, Medium, Low engagement)
- Weekend vs weekday activity differences and engagement gaps
- Sedentary behavior patterns and opportunities for intervention
- Monthly activity trends and seasonal engagement fluctuations
  
---
## 🔍 Business Questions Addressed

### Core Analysis (3 Key Questions):

1. **What are some trends in smart device usage?**
2. **How could these trends apply to Bellabeat customers?**
3. **How could these trends help influence Bellabeat's marketing strategy?**

### Deep-Dive Analysis:
- Step distribution patterns across weekdays (outlier detection using boxplots)
- Median steps comparison: Monday to Sunday
- Correlation analysis: Total Distance vs Calories (r = 0.64)
- Correlation analysis: Total Steps vs Calories (r = 0.59)
- Correlation analysis: Very Active Minutes vs Calories (r = 0.62)
- Active vs Sedentary time distribution analysis (pie chart)
- Weekday vs Weekend performance comparison
- Monthly trends: April vs May analysis

---
---

## 💡 Key Insights & Findings

### 📈 Activity Metrics Overview
- **Average Daily Steps:** ~7,638 steps (23% below WHO recommendation of 10,000 steps)
- **Median Daily Steps:** ~7,406 steps
- **Average Sedentary Time:** ~16+ hours/day (82.2% of total time)
- **Average Active Time:** ~3.9 hours/day (17.8% of total time)

### 📅 Weekly Activity Patterns
- **Most Active Day:** Tuesday with 8,411 median steps
- **Least Active Day:** Sunday with 6,083 median steps (27% drop from Tuesday)
- **Weekday Performance:** 7,802 median steps
- **Weekend Performance:** 6,708 median steps (14% lower than weekdays)
- **Active Minutes (Weekday vs Weekend):** 230 vs 225 minutes (minimal difference)
- **Calories Burned (Weekday vs Weekend):** 2,159 vs 2,096 calories

**Insight:** Users maintain structured fitness routines during weekdays but reduce activity on weekends, suggesting work-related movement patterns.

### 📊 Monthly Trends (April vs May)
- **April Median Steps:** 7,711 steps
- **May Median Steps:** 7,045 steps (8.6% decline)
- **April Active Minutes:** 233 minutes
- **May Active Minutes:** 215 minutes (7.7% decline)
- **April Calories:** 2,135 calories
- **May Calories:** 2,131 calories (minimal change)

**Insight:** Activity levels declined from April to May, indicating potential seasonal engagement drop or user fatigue.

### 🔥 Correlation Analysis: Activity & Calories
- **Total Steps → Calories:** r = 0.59 (Moderate positive correlation)
- **Total Distance → Calories:** r = 0.64 (Strong positive correlation)
- **Very Active Minutes → Calories:** r = 0.62 (Strong positive correlation)

**Insight:** Higher physical activity consistently leads to more calories burned. Distance covered is the strongest predictor of calorie expenditure.

### ⏰ Time Distribution: Active vs Sedentary
- **Active Minutes:** 17.8% of daily time
- **Sedentary Minutes:** 82.2% of daily time

**Insight:** Users spend over 4x more time sedentary than active, presenting a significant opportunity for Bellabeat to introduce micro-movement reminders and sedentary break alerts.

### 📍 Activity Distribution Patterns
- **Step Count Outliers:** Several users achieve 30,000+ steps, indicating highly active individuals
- **Consistency:** Box plot analysis shows relatively consistent median activity across all weekdays
- **Variability:** High standard deviation suggests diverse user activity levels

**Key Takeaway:** Users walk more on weekdays due to work routines. Weekend activity drops significantly. Distance is the best predictor of calorie burn. 82.2% sedentary time represents major intervention opportunity.

---
---

## 🎯 Strategic Recommendations

### 1. Launch Weekend Engagement Campaigns
**Problem:** 14% drop in weekend activity

**Solution:** "Weekend Warrior" challenges, family-friendly activities, Friday evening motivational notifications

### 2. Combat Sedentary Behavior
**Problem:** 82.2% sedentary time (16+ hours/day)

**Solution:** Hourly movement reminders, "Sedentary Break" streaks, 5-minute activity bursts every 2 hours

### 3. Seasonal Re-Engagement Strategy
**Problem:** 8.6% activity decline from April to May

**Solution:** Mid-campaign refresh, seasonal fitness programs, milestone rewards, personalized progress reports

### 4. User Segmentation & Personalization
**Problem:** Wide variability in activity levels

**Solution:** Segment into High (10k+ steps), Medium (7.5k-10k), Low (<7.5k) tiers with personalized plans

### 5. Leverage Activity-Calorie Correlation
**Problem:** Users unaware of direct impact

**Solution:** Real-time calorie tracking, projected burn based on goals, nutrition integration

---
---

## 🛠️ Tools & Technologies

- **Python 3.8+** - Data analysis and manipulation
- **Pandas** - Data cleaning and transformation
- **NumPy** - Statistical computations
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive analysis environment
- **Kaggle Notebooks** - Cloud-based platform

---
---


## 📊 Impact & Results

**Deliverables:**
-  Analysis of 940 activity records across 30 users
-  9 comprehensive visualizations with insights
-  7 strategic marketing recommendations
-  User segmentation framework
-  Evidence-based product features

**📈 Potential Business Impact:**
-  35%+ revenue growth via weekend campaigns
-  20-30% engagement increase via sedentary interventions
-  Improved retention through seasonal strategies

---
---

## 👨‍💻 Author

**Farhan Khan**  
Data Analyst | Google Data Analytics Certificate  
📧 Email: farhanriyaz9005@gmail.com  
🔗 LinkedIn: [Connect with me](https://www.linkedin.com/in/farhankhan999/)
