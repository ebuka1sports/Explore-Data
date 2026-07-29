# 📊 Explore Data Projects

This repository contains two distinct data analysis projects focused on academic grading metrics and sports analytics.

---

## ⚽ Project 1: Premier League Data Analysis (`PLProjectOne.ipynb`)

### 🏆 Overview
This project analyzes Premier League match data using Python and Pandas inside Visual Studio Code. The dataset contains match‑level information such as `HomeTeam`, `AwayTeam`, `FTHG` (Full‑Time Home Goals), and `FTAG` (Full‑Time Away Goals). The goal is to transform raw match data into meaningful football insights, including team performance, goals, and a final league table.

### 🎯 Objectives
The project focuses on answering key football analytics questions:
* **Total goals scored by each team:** Combining home and away goals to compute overall attacking performance.
* **Total goals conceded:** Measuring defensive strength by summing goals conceded at home and away.
* **Home and away performance:** Calculating Home/Away wins, losses, and draws.
* **Final league table:** Building a complete league table with Position, Team, Total Wins, Total Losses, Goals Scored, Goals Conceded, Points (3 for win, 1 for draw), and Goal Difference.

*Note: The table is sorted using official Premier League rules: Points, Goal Difference, then Goals Scored.*

### 📊 Visualizations
The project includes charts to help interpret team performance, such as:
* Horizontal bar charts for away wins.
* Additional charts for goals scored, goals conceded, and win/loss comparisons.

---

## 🎓 Project 2: Student Grades Data Analysis (`student_data.ipynb`)

### 📝 Overview
An analysis of student performance, demographics, and grading metrics using Jupyter Notebooks to identify academic trends and score distributions.

### 📂 Associated Data Files
* `Grades_data.csv`
* `PLProject1Data.csv`
* `Key to results data.txt`

---

## 🛠️ Tools & Technologies
* **Python 3**
* **Pandas** for data manipulation
* **Matplotlib & Seaborn** for visualizations
* **VS Code & Jupyter Notebooks** as the development environment

## 🚀 How to Run
1. Clone this repository or download the files.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib seaborn notebook
   ```
3. Open your terminal in this folder and start Jupyter:
   ```bash
   jupyter notebook
   ```
4. Click on either `PLProjectOne.ipynb` or `student_data.ipynb` to view the analysis.
