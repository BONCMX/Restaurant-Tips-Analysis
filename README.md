# 🍽️ Restaurant Tips Analysis
![image](https://github.com/user-attachments/assets/075aed6c-b3ab-4f86-8b18-b744fae76a44)

##Introduction
This project aims to use the restaurant tips dataset to practice creating composition plots and visualizations. We will examine the relationship between different variables and the tips given.

The dataset consists of information from 244 restaurant bills, collected in the US in 1987.

It includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.
This project analyzes tipping behavior in restaurants using a real-world dataset.  
We explore how different factors such as gender, smoking status, day of the week, and meal time affect the tip amount.  
The goal is to extract actionable insights using Python and visualize the findings with matplotlib.

---

## 📂 Dataset Information

- **Source**: [CSV File - GitHub Public Repository](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv)
- **Size**: 244 rows × 8 columns
- **Collected**: USA, year 1987
- **Attributes**:
  - `id`: Unique ID of the bill
  - `total_bill`: Total bill amount
  - `tip`: Tip amount given
  - `sex`: Gender of the bill payer
  - `smoker`: Smoker status of the payer
  - `day`: Day of the week
  - `time`: Lunch or Dinner
  - `size`: Number of people at the table

> You can directly access the dataset via the above URL, or load it in code using:  
```python
pd.read_csv('https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv')
```

---

## 🎯 Project Objectives
- Understand how different variables influence tip amounts
- Compare tip distribution across:
  - Smokers vs Non-Smokers
  - Male vs Female
  - Weekday vs Weekend
  - Lunch vs Dinner
- Use histograms and statistical summaries (mean, median) for comparison
- Generate actionable insights from data

---

## 📊 Key Findings

### ✅ Insight 1: Smokers vs Non-Smokers
- **Smokers tip more** on average (both mean and median).
- Smokers have **wider tip distributions**, with more large values.
- Non-smokers rarely tip more than $9.

### ✅ Insight 2: Gender Comparison
- **Male customers tip more** than females on average.
- Tipping behavior among males is more spread out and includes more generous values.

### ✅ Insight 3: Weekday vs Weekend
- **Tips are higher on weekends**.
- Weekday tips are more concentrated under $6.7.
- Weekend tipping has more frequent high-value outliers.

### ✅ Insight 4: Lunch vs Dinner
- **Dinner receives higher tips** than lunch.
- Dinner tips are more distributed and skewed towards high values.
- Lunch is often more practical and lower-value.

> 📍 These insights were derived from visualizations and central tendency statistics.

---

## 📷 Sample Visualization
Tip distribution by smoking status:

![Tip Distribution - Smokers vs Non-Smokers](images/smokers_vs_nonsmokers.png)
