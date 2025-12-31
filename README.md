# 📊 ML Test Score Analysis — Batch-wise Performance Insights

## 🧩 Problem Statement
The objective of this project is to analyze **ML test scores across three different batches** and derive meaningful insights about:
- Overall performance
- Consistency of learning outcomes
- Presence of high and low performers  

This is an **open-ended analytical problem**, where the focus is not on a single metric but on understanding **score distributions and patterns** across batches.

---

## 📁 Dataset Overview
- **File:** `scores_data.csv`
- **Records:** Individual student test scores
- **Score Format:** `x / 7` (maximum score = 7)

### Columns
| Column | Description |
|------|------------|
| Batch | Batch identifier |
| User_ID | Unique student ID |
| Score | Test score in x / 7 format |

---

## 🧠 Analysis Approach
The analysis follows a structured, real-world data science workflow:

1. **Data Validation**
   - Verified schema and data types
   - Checked score ranges and batch counts

2. **Data Cleaning**
   - Converted score strings (`x / 7`) into numeric values
   - Ensured consistency across batches

3. **Exploratory Data Analysis (EDA)**
   - Batch-wise mean, median, standard deviation
   - Percentile analysis (25th, 50th, 75th, 90th)
   - Distribution analysis using histograms and boxplots

4. **Performance Segmentation**
   - High performers (≥ 6 / 7)
   - Medium performers (4–5 / 7)
   - Low performers (≤ 3 / 7)

5. **Insight Generation**
   - Compared batches across multiple dimensions
   - Identified strengths, risks, and improvement areas

---

## 📈 Key Insights
- One batch demonstrates **strong and consistent performance**, with most students scoring near full marks.
- One batch shows **high variance**, indicating uneven understanding among students.
- One batch is **consistent but underperforms at the top end**, suggesting the need for deeper conceptual reinforcement.

> The analysis highlights why relying only on averages can be misleading and emphasizes the importance of distribution-based reasoning.

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## ▶️ How to Run the Project
1. Clone the repository
2. Open the notebook: Analysis_on_ML_Test_Scores.ipynb
3. Run cells sequentially to reproduce the analysis and visualizations

---

## 🎯 Outcome & Learning
This project demonstrates:
- Strong exploratory data analysis skills
- Distribution-centric thinking instead of mean-only analysis
- Ability to convert raw scores into actionable insights
- Clear analytical storytelling for open-ended problems

---

## 📌 Use Case
This type of analysis is relevant for:
- Educational performance evaluation
- Batch or cohort comparison
- Learning outcome assessment
- Data-driven decision making in training programs

---

🙋‍♂️ Author

Divya Kathare
SQL • Data Analyst • Data Science Enthusiast

GitHub: https://github.com/Divya-Kathare

LinkedIn: https://www.linkedin.com/in/divya-kathare-41323a3a0
---

⭐ If you find this project useful, feel free to star the repository.

