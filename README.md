# 🧠 Exploratory Data Analysis of Employee Salaries

## 🔍 Project Summary

In this project, I analyzed a small dataset of 26 employees to explore how their annual salaries relate to their departments. The main goal was to see how salaries are spread out in the company, spot any unusual values (outliers), and find out which departments pay more or less.

## 📊 What I Did and Found

## 1. Looking at All Salaries (Salary_Annually)

I started by looking at all the salaries to understand the company’s overall pay scale.

Important numbers:

Average (Mean) Salary: $288,595.46

Middle (Median) Salary: $279,988.50

Lowest Salary: $106,781.00

Highest Salary: $659,321.00

Standard Deviation: $141,026.85 (shows salaries are very spread out)

The average is higher than the median because a few people have very high salaries — so the dataset is “right-skewed” (more low salaries and some very high ones). I confirmed this with a histogram and box plot.

## 2. Employee Count by Department

I checked how many employees were in each department.

Example:

IT has the most employees (5 people)

Quality Assurance has just 1 person

Departments like Finance, HR, Legal, Customer Support each have 3 employees

## 3. Comparing Salary and Department (Scatter Plot)

I combined the salary and department data using a scatter plot to see who earns what in each department.

2 Important Discoveries:

## Big Outlier:
The highest salary ($659,321) belongs to someone in HR. This one person earns way more than others and is affecting the average salary a lot.

## Salary Differences by Department:

Legal: 3 employees, all making around $350,000 — very tightly grouped.

Quality Assurance: Only 1 employee, but they make about $550,000.

IT: People earn between $200,000–$500,000 — the widest range.

Operations & Customer Support: These employees earn the least (mostly under $200,000).
