# CS105 Fall 2025 Team 7 Mini Project Report

**Author: Lydia Niu, Ryan Kim, Jonathan Chun, Stuart Arief, Colin Pham** [cite: 1254]

---

## 📝 Project Overview

This project was a mini-project for CS105 in Fall 2025, UCR. The core research explored the factors influencing UCR students' mental health evaluation, imposter syndrome scale, nutrient consumption, and food preferences. 

## 🎯 Key Research Questions

The analysis focused on several key hypotheses and exploratory data analysis (EDA) topics:

* [cite_start]The relationship between an individual's mental health rating and their commuting distance to campus[cite: 1256].
* [cite_start]The connection between a student's self-reported **Imposter Syndrome** level, overall **mental health**, and **caffeine intake**[cite: 1262].
* [cite_start]The correlation between a student's daily **caffeine consumption** and their **frequency of eating campus meals**[cite: 1257].
* [cite_start]A comparison of health habits (caffeine, sleep, and skipped breakfast) between **Data Science** and **Computer Science** students[cite: 1259].
* [cite_start]The association between a student's **cuisine preference region** and their **on-campus dining choices**[cite: 1261].
* [cite_start]Whether a student's **ethnic background** shows a statistically significant correlation with their **cuisine preference**[cite: 1260].

## 📊 Exploratory Data Analysis (EDA) & Key Findings

| Topic | Analysis Method | Finding |
| :--- | :--- | :--- |
| **Mental Health vs. Commuting Distance** | Scatterplot | [cite_start]**No significant relation** was found between mental health rating (1-5) and commute distance (in miles)[cite: 1391]. |
| **Mental Health vs. Imposter Syndrome** | Violin Plot | **Clear negative correlation:** Overall mental health declines as a student's self-rated imposter syndrome increases. [cite_start]Students with higher syndrome ratings (4-5) clustered around lower mental health scores (2-3)[cite: 1439, 1440]. |
| **Caffeine vs. Imposter Syndrome** | Violin Plot | [cite_start]**No strong correlation.** Caffeine consumption is highly individualized and not strongly linked to imposter syndrome ratings[cite: 1501, 1504]. |
| **Caffeine vs. Campus Meal Frequency** | Scatterplot | [cite_start]**Negative correlation:** As daily caffeine consumption increases, a student is less likely to eat from campus food places[cite: 1514, 1515]. |
| **CS vs. DS Health Habits** | Parallel Coordinate Plot | [cite_start]Data Science and Computer Science students showed similar average caffeine consumption and hours of sleep, but **Data Science students skip breakfast at a slightly higher frequency**[cite: 1528, 1529]. |
| **Cuisine Preference vs. On-Campus Dining** | Heatmap/Radar Chart | [cite_start]Students who prefer **European and Latin American** cuisines are more frequent visitors to corresponding on-campus restaurants (e.g., Subway and Chronic Taco)[cite: 1145]. [cite_start]Students who favor **Fusion/Other cuisines** find fewer matching on-campus options[cite: 1146]. |
| **Ethnicity vs. Cuisine Preference** | Stacked Bar / Chi-Square Test | [cite_start]The Chi-square test indicated **no statistical significance** between a student's ethnic background and their cuisine preference, leading to a failure to reject the null hypothesis[cite: 1210, 1211]. |

## 📦 Data & Variables

The analysis utilized a dataset compiled from a student survey, featuring both numerical and categorical data:

* [cite_start]**Mental Health rating** (1-5) [cite: 1264]
* [cite_start]**Commute distance** to campus (miles) [cite: 1265]
* [cite_start]Average **Caffeine consumption** (mg per day) [cite: 1266]
* [cite_start]Campus food **meal consumption rate** (times per week) [cite: 1267]
* [cite_start]**Imposter syndrome** rating (1-5) [cite: 1268]
* [cite_start]**Ethnicity** survey (Categorical data) [cite: 1269]

## 🛠️ Technologies & Libraries

The project was implemented in a Jupyter Notebook using Python and standard data science libraries:

* `pandas`
* `matplotlib.pyplot`
* `numpy`
* `seaborn`
* `scipy.stats` (for statistical tests)
* `re` (for data cleaning)
