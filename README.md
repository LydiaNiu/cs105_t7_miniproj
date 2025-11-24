# CS105 Fall 2025 Team 7 Mini Project Report

**Author: Lydia Niu, Ryan Kim, Jonathan Chun, Stuart Arief, Colin Pham** 

---

## 📝 Project Overview

This project was a mini-project for CS105 in Fall 2025, UCR. The core research explored the factors influencing UCR students' mental health evaluation, imposter syndrome scale, nutrient consumption, and food preferences. 

A major initial phase involved designing a great survey from scratch to collect a robust set of samples. 

The data analysis involved a comprehensive Exploratory Data Analysis (EDA), utilizing 6 different visualization types across a total of 9 figures to rigorously test our hypotheses and uncover patterns and correlations within the data.

## 🎯 Key Research Questions

The analysis focused on several key hypotheses and exploratory data analysis (EDA) topics:

* The relationship between an individual's mental health rating and their commuting distance to campus.
* The connection between a student's self-reported **Imposter Syndrome** level, overall **mental health**, and **caffeine intake**.
* The correlation between a student's daily **caffeine consumption** and their **frequency of eating campus meals**.
* A comparison of health habits (caffeine, sleep, and skipped breakfast) between **Data Science** and **Computer Science** students.
* The association between a student's **cuisine preference region** and their **on-campus dining choices**.
* Whether a student's **ethnic background** shows a statistically significant correlation with their **cuisine preference**.

## 📊 Exploratory Data Analysis (EDA) & Key Findings

| Topic | Analysis Method | Finding |
| :--- | :--- | :--- |
| **Mental Health vs. Commuting Distance** | Scatterplot | **No significant relation** was found between mental health rating (1-5) and commute distance (in miles). |
| **Mental Health vs. Imposter Syndrome** | Violin Plot | **Clear negative correlation:** Overall mental health declines as a student's self-rated imposter syndrome increases. Students with higher syndrome ratings (4-5) clustered around lower mental health scores (2-3). |
| **Caffeine vs. Imposter Syndrome** | Violin Plot | **No strong correlation.** Caffeine consumption is highly individualized and not strongly linked to imposter syndrome ratings. |
| **Caffeine vs. Campus Meal Frequency** | Scatterplot | **Negative correlation:** As daily caffeine consumption increases, a student is less likely to eat from campus food places. |
| **CS vs. DS Health Habits** | Parallel Coordinate Plot | Data Science and Computer Science students showed similar average caffeine consumption and hours of sleep, but **Data Science students skip breakfast at a slightly higher frequency**. |
| **Cuisine Preference vs. On-Campus Dining** | Heatmap/Radar Chart | Students who prefer **European and Latin American** cuisines are more frequent visitors to corresponding on-campus restaurants (e.g., Subway and Chronic Taco). Students who favor **Fusion/Other cuisines** find fewer matching on-campus options. |
| **Ethnicity vs. Cuisine Preference** | Stacked Bar / Chi-Square Test | The Chi-square test indicated **no statistical significance** between a student's ethnic background and their cuisine preference, leading to a failure to reject the null hypothesis. |

## 📦 Data & Variables

The analysis utilized a dataset compiled from a student survey, featuring both numerical and categorical data:

* **Mental Health rating** (1-5) 
* **Commute distance** to campus (miles) 
* Average **Caffeine consumption** (mg per day)
* Campus food **meal consumption rate** (times per week)
* **Imposter syndrome** rating (1-5)
* **Ethnicity** survey (Categorical data)

## 🛠️ Technologies & Libraries

The project was implemented in a Jupyter Notebook using Python and standard data science libraries:

* `pandas`
* `matplotlib.pyplot`
* `numpy`
* `seaborn`
* `scipy.stats` (for statistical tests)
* `re` (for data cleaning)
