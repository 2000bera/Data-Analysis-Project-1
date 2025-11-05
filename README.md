# 🧠 Exploratory Data Analysis of Employee Salaries

## 🔍 Project Summary

In this project, I analyzed a small dataset of 26 employees (**DUMMY DATA**) to explore how their annual salaries relate to their departments. The main goal was to see how salaries are spread out in the company, spot any unusual values (outliers), and find out which departments pay more or less.

## 🛠 Tools used
- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab for notebook

https://colab.research.google.com/drive/1zQPCUBua2xwpq50EBWQYyjeZ5xhvKEJL#scrollTo=Xl913sn-05wb

## 📊 What I Did and Found

## 1. Looking at All Salaries (Salary_Annually)

I started by looking at all the salaries to understand the company’s overall pay scale.

Important numbers:

Average (Mean) Salary: R288,595.46

Middle (Median) Salary: R279,988.50

Lowest Salary: R106,781.00

Highest Salary: R659,321.00

Standard Deviation: R141,026.85 (shows salaries are very spread out)


<img width="323" height="327" alt="image" src="https://github.com/user-attachments/assets/c200e7aa-47df-4653-b935-3440a0aac6f8" />


The average is higher than the median because a few people have very high salaries — so the dataset is “right-skewed” (more low salaries and some very high ones). I confirmed this with box plot.

<img width="834" height="536" alt="image" src="https://github.com/user-attachments/assets/bda08a3d-f40a-46ec-bdb8-350549aabafc" />


## 2. Employee Count by Department

I checked how many employees were in each department.

Example:

IT has the most employees (5 people)

Quality Assurance has just 1 person

Departments like Finance, HR, Legal, Customer Support each have 3 employees


<img width="264" height="473" alt="image" src="https://github.com/user-attachments/assets/fa02245b-5e97-4d2b-be23-88bf750421c9" />


## 3. Comparing Salary and Department (Scatter Plot)

I combined the salary and department data using a scatter plot to see who earns what in each department.

2 Important Discoveries:

Big Outlier:
The highest salary (R659,321) belongs to someone in HR. This one person earns way more than others and is affecting the average salary a lot.

## Salary Differences by Department:

Legal: 3 employees, all making around R350,000

Quality Assurance: Only 1 employee, but they make about R550,000.

IT: People earn between R200,000–R500,000 — the widest range.

Operations & Customer Support: These employees earn the least (mostly under R200,000).

<img width="806" height="516" alt="image" src="https://github.com/user-attachments/assets/e459bc72-3cc1-4282-a50b-0ddd855489aa" />

