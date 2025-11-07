Predicting Student Loan Delinquency Post-CARES Act Using SHED Data

Author: Heather F. Weston
Institution: Western Governors University

📌 Project Overview

This project explores the predictors of student loan delinquency using microdata from the Federal Reserve’s Survey of Household Economics and Decisionmaking (SHED), covering survey years from 2015 to 2024.

The central research question is:

What borrower characteristics and financial indicators are most predictive of student loan delinquency, and how do these patterns differ before and after the COVID-19 payment pause?

The goal is to help policymakers and loan servicers better understand and address borrower risk in the evolving post-pandemic landscape.

🔍 Key Features

Descriptive, diagnostic, and predictive analytics

Logistic regression modeling across three time periods:

Pre-CARES Act (2015–2019)

Post-resumption of payments (2023–2024)

Combined period model (2015–2024)

Feature importance and trend comparison across demographics, income, credit stress, and repayment behavior

Visual storytelling using bar charts, heatmaps, ROC curves, and coefficient plots

Actionable insights around high-risk borrower profiles and equity-driven repayment policy design

🧠 Technical Details

Language: Python

Environment: Jupyter Notebook

Libraries:

pandas, numpy – data handling

matplotlib, seaborn – visualization

scikit-learn – modeling

statsmodels – statistical inference

📊 Data Sources

Survey of Household Economics and Decisionmaking (SHED) — Microdata (2015–2024)

Federal Student Aid Loan Portfolio — Aggregate delinquency statistics (contextual use only)

All datasets used are publicly available and non-personally identifiable.

📈 Results Summary

Logistic regression models achieved ROC-AUC scores > 0.70, indicating good predictive power across all time periods.

Most consistent predictors of delinquency:

Low income levels (especially <$40K)

Financial insecurity

Racial/ethnic minority status (particularly Black and Hispanic borrowers)

The combined model (2015–2024) offered the best balance between recall and precision, making it strongest for early risk detection.

🎯 Recommendations

Deploy high-recall models to flag at-risk borrowers early, even if at the cost of lower precision.

Enhance equity-based repayment policies, such as automatic enrollment in income-driven plans and tailored outreach for high-risk demographic groups.

🚀 Running the Project

Clone this repo:

git clone https://github.com/yourusername/student-loan-delinquency-prediction.git


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook and run the analysis:

jupyter notebook analysis.ipynb

📂 Repo Structure
.
├── data/
│   └── shed_2015_2024.csv (optional placeholder)
├── notebooks/
│   └── analysis.ipynb
├── README.md
├── requirements.txt
└── src/
    └── preprocessing.py

📺 Presentation

A full walkthrough of the analysis and findings is available on Panopto:
https://wgu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=b5672e81-7f8a-474e-a461-b32c01163aa6

(Accessible to WGU students only)

📝 License

This project is licensed under the MIT License — feel free to use or adapt the code for non-commercial, educational, or research purposes.

📚 References

Federal Reserve SHED Data (Survey of Household Economics and Decisionmaking, 2025)

Federal Student Aid Loan Portfolio (2025)