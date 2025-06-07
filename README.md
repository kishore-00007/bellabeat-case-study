# 📊 Bellabeat Case Study – Data Analysis with R

## 📝 Project Overview
This project is part of the **Google Data Analytics Professional Certificate**.  
We analyze smart device usage data from FitBit to help Bellabeat, a wellness-focused tech company, better understand user behavior and design a targeted marketing strategy.

---

## 🎯 Objective
- Analyze users’ daily activity, sleep, and weight data using R
- Discover usage patterns that can guide Bellabeat's marketing decisions
- Visualize findings through clear and informative plots

---

## 🛠 Tools & Technologies
- **Language:** R
- **Environment:** RStudio
- **Libraries:** `tidyverse`, `lubridate`, `janitor`, `ggplot2`
- **Visualization Output:** Histogram, Scatter Plot, Summary Stats
- **Data Format:** CSV

---

## 📁 Dataset
- **Source:** [FitBit Fitness Tracker Data (via Kaggle)](https://www.kaggle.com/datasets/arashnic/fitbit)
- Data includes:  
  - `dailyActivity_merged.csv`  
  - `sleepDay_merged.csv`  
  - `weightLogInfo_merged.csv`
- Data covers 30+ days of usage from 33 FitBit users

---

## 🔍 Process

### 1. **Ask**
- How do users interact with their smart devices?
- What are the patterns in physical activity, sleep, and calories burned?

### 2. **Prepare**
- Imported and cleaned data using `janitor::clean_names()`
- Converted date formats using `lubridate`
- Removed duplicate entries
- Checked for missing values

### 3. **Process**
- Standardized column names
- Removed NA values
- Joined data where relevant
- Performed descriptive analysis

### 4. **Analyze**
- Calculated average, median, min, and max steps
- Identified sleep behavior trends
- Examined relationship between very active minutes and calories burned

### 5. **Visualize**
- 📈 `steps_distribution.png`  
- 📉 `active_minutes_vs_calories.png`  
- 😴 `sleep_distribution.png`

### 6. **Share**
- Included all charts in `/plots` folder
- Key insights and recommendations below

---

## 📈 Key Findings

- Most users **do not reach 10,000 steps/day** – Bellabeat could promote daily goals.
- There's a **positive correlation between very active minutes and calories burned** – highlight this in app messaging.
- Average sleep time is around **7 hours**, with a wide distribution – sleep quality could be a focus.
- Activity and sleep patterns vary significantly between users – segmentation may help marketing.

---

## 💡 Recommendations

1. Promote daily activity goals through in-app badges and notifications.
2. Highlight benefits of increased activity for better calorie burn and improved sleep.
3. Design campaigns encouraging better sleep routines using Bellabeat features.
4. Offer rewards or challenges to improve user engagement during weekends or low-activity days.

---

## 👨‍💻 Author

**Kishore Suresh**  
🎓 BBA Graduate | 📊 Aspiring Data Analyst  
📌 Tools: SQL | Excel | Tableau | R  
🌐 GitHub: [> click here](https://github.com/kishore-00007)  
📫 Email: [> kishore00007s@gmail.com](mailto:kishore00007s@gmail.com)  
🔗 LinkedIn: [> bit.ly/kishore-linkedin](https://bit.ly/kishore-linkedin)
---

## 📂 File Structure
