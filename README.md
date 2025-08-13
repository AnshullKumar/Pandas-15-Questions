# 📊 Learn Pandas in 15 Questions — Summary from LeetCode

A concise summary of the [Medium article by Kawsar Hossain](https://kawsar34.medium.com/learn-pandas-in-15-questions-from-leetcode-c8d0d10c2f0a) that teaches Pandas concepts through 15 LeetCode problems.  
This repo contains the notes, explanations, and example solutions for quick revision.

---

## 🗂 Table of Contents
1. [Overview](#overview)
2. [Core Pandas Functions Covered](#core-pandas-functions-covered)
3. [15 Questions Summary](#15-questions-summary)
4. [Practice](#practice)
5. [References](#references)

---

## Overview
This guide covers **Pandas DataFrame operations** often asked in LeetCode's Pandas problems.  
Each question introduces new methods for **data manipulation, filtering, grouping, and transformation**.

---

## Core Pandas Functions Covered
- `rename()` → Rename columns or index labels
- `merge()` → Combine two DataFrames (SQL-style joins)
- `drop_duplicates()` → Remove duplicate rows
- `sort_values()` → Sort by one or more columns
- `groupby()` + `agg()` → Group and aggregate data
- `fillna()` → Handle missing values
- `round()` → Round numerical values
- `apply()` → Apply custom functions row-wise or column-wise
- `rank()` → Assign ranks to rows
- `loc[]` / `iloc[]` → Access rows/columns by label or index

---

## 15 Questions Summary

| # | Problem Title (LeetCode) | Concept Used | Notes |
|---|--------------------------|--------------|-------|
| 1 | Reformat Department Table | `pivot_table()` | Convert long format to wide format |
| 2 | Find Customer Referee | Boolean filtering | Filter with conditions |
| 3 | Biggest Single Number | `drop_duplicates()` + `max()` | Find max unique value |
| 4 | Customers Who Never Order | `merge()` + filtering | Left join and filter nulls |
| 5 | Employees Earning More Than Their Managers | Self join | Compare salaries |
| 6 | Duplicate Emails | `groupby()` + `count()` | Find repeated values |
| 7 | Customers Who Bought All Products | `groupby()` + `nunique()` | Compare counts |
| 8 | Product Sales Analysis I | `groupby()` + `sum()` | Aggregate sales |
| 9 | Classes More Than 5 Students | `groupby()` + filtering | Count and filter groups |
| 10 | Find Followers Count | `groupby()` + `count()` | Social media follower stats |
| 11 | Sales Analysis II | Filtering with conditions | Multiple filter conditions |
| 12 | Sales Analysis III | Filtering by min/max | Date and price filters |
| 13 | Managers with at Least 5 Direct Reports | Self join + count | Org chart analysis |
| 14 | Average Selling Price | `merge()` + `groupby()` | Compute averages |
| 15 | Confirmation Rate | `groupby()` + `mean()` | Percentage-based metric |

---

## Practice
- 🐍 Solving the problems directly on [LeetCode Pandas Section](https://leetcode.com/problemset/database/?page=1&topicSlugs=pandas).
- 📓 Trying them in **Google Colab** for interactive learning.
- 💡 Bonus: Modify the problems with your own datasets.

---

## References
- Original article: [Learn Pandas in 15 Questions from LeetCode](https://kawsar34.medium.com/learn-pandas-in-15-questions-from-leetcode-c8d0d10c2f0a)
- Pandas Docs: [https://pandas.pydata.org/docs](https://pandas.pydata.org/docs)


- Original article: [Learn Pandas in 15 Questions from LeetCode](https://kawsar34.medium.com/learn-pandas-in-15-questions-from-leetcode-c8d0d10c2f0a)
- Pandas Docs: [https://pandas.pydata.org/docs](https://pandas.pydata.org/docs)

---
