# 🍽️ Restaurant Tips Analysis
![image](https://github.com/user-attachments/assets/075aed6c-b3ab-4f86-8b18-b744fae76a44)

## Introduction
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
```
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

## 🎯 Main Goals
- Investigate whether tipping behavior differs between smokers and non-smokers
- Examine how gender influences tip amount
- Compare weekday and weekend tipping patterns
- Analyze the difference between lunch and dinner tipping
- Summarize the above insights into actionable findings

---

## 📷Visualization & Insights ✅
 
- **Tip distribution by smoking status:**
![image](https://github.com/user-attachments/assets/07f3f3ce-c546-46ea-8d65-3f206d2c0fbe)
- Smokers tend to give higher tips on average.
- The distribution for smokers is wider, indicating a more generous subgroup.
- Non-smokers rarely tip above $9.
---  
- **Tip distribution by gender status:**
![image](https://github.com/user-attachments/assets/296202b9-ef5f-402c-8a8b-fef7fee0137c)
- Males consistently show higher tip means and medians than females.
- Male tip distribution includes more frequent mid- to high-range tips.
---
- **Tip distribution by weekend status:**
![image](https://github.com/user-attachments/assets/7c85e58d-94db-44c7-923e-eebc18648508)
- Weekend customers tend to tip more generously than weekday diners.
- Tip amounts are more concentrated and lower on weekdays.
---
- **Tip distribution by meal status:**
![image](https://github.com/user-attachments/assets/14ded6b8-003b-42d4-a841-062a2f3cffb7)
- Dinner has higher mean and median tip values.
- Tips are more widely distributed at dinner, possibly reflecting celebratory or social contexts.




