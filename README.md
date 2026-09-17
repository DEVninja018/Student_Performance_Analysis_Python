Welcome🙏

# Student_Performance_Analysis_Python
The Student Performance Analysis project is a data-driven application designed to automate and simplify the evaluation of academic progress.This project uses Python to perform Exploratory Data Analysis (EDA), clean raw student records, engineer meaningful new features


## 🎯 Objectives
*   **Analyze Dataset Quality:** Clean missing, duplicate, or irregular entries within the data.(there were none,btw)
*   **Uncover Key Drivers:** Evaluate how demographic traits, parental education, lunch types etc influence final scores.
*   **Performance Comparison:** Compare average distributions across math, reading, and writing scores.
*   **Actionable Insights** 


```text
├──  StudentsPerformance.csv     # Raw dataset file
├──  Student_Performance_Analysis.ipynb # Complete Jupyter Notebook with code
├── README.md                     # Project documentation
└── studentperformancedashboard.pbix          #Power BI dashboard 
```

## 📊 Dataset Description
The dataset contains information on 1,000 students and their scores across three subjects. It consists of **8 core attributes**:

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `gender` | Categorical | Sex of the student (Male/Female) |
| `race/ethnicity` | Categorical | Ethnic group categorization (Group A to E) |
| `parental level of education` | Categorical | Highest education tier achieved by parents |
| `lunch` | Categorical | Type of lunch status (Standard or Free/Reduced) |
| `test preparation course` | Categorical | Completion status of prep course (Completed/None) |
| `math score` | Numerical | Grade obtained in Mathematics (0–100) |
| `reading score` | Numerical | Grade obtained in Reading (0–100) |
| `writing score` | Numerical | Grade obtained in Writing (0–100) |


## 🛠️ Tech Stack & Dependencies
*   **Language:** Python (ofc 😅)
*   **Libraries:** 
    *   `pandas` (Data manipulation)
    *   `numpy` (Numerical analysis)
    *   `matplotlib` & `seaborn` (Data visualization)
    *   `scipy` (Statistical testing)

## 💡 Key Findings
*   **Test Preparation Effectiveness:** Students who completed the test preparation course scored significantly higher on average across all subjects than those who did not.
*   **Socio-economic Impact:** Students receiving a standard lunch consistently outperformed peers on free/reduced lunch options, suggesting economic stability impacts learning baselines.
*   **Parental Influence:** A direct linear relationship was observed between a parent's education level and the average score matrix achieved by the student.

Happy learning!!!!!🚀
