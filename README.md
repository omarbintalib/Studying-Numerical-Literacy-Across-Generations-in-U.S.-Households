# Studying Numerical Literacy Across Generations in U.S. Households

## 📊 Project Overview
Numerical literacy—the ability to understand and work with numbers—is a foundational skill with long-term implications for economic well-being. This project utilizes multi-generational data from the **Panel Study of Income Dynamics (PSID)** and the **Child Development Supplement (CDS)** to investigate how these skills are transmitted from parents to children and their correlation with adult wealth.

By linking individuals' childhood numerical literacy to their adult outcomes and their children's skills, we constructed matched longitudinal and parent-child pairs to identify the family environments that shape quantitative proficiency.

## 🛠️ Key Technical Contributions
* **End-to-End Data Engineering**: Merged complex, longitudinal PSID and CDS datasets across multiple survey waves (1970–2025).
* **Pipeline Optimization**: Designed a memory-aware chunking pipeline to handle large-scale joins across datasets efficiently.
* **Feature Engineering**: Harmonized disparate test-score scales and constructed high-impact socioeconomic indicators.
* **Predictive Modeling**: Implemented and optimized several machine learning models, including **XGBoost**, **Random Forest**, and **Gradient Boosting**.
* **Deep Learning**: Integrated **PyTorch** for advanced predictive analysis.
* **Data Preprocessing**: Managed complex missing-data imputation and performed exploratory data analysis (EDA) to ensure dataset integrity.

## 💻 Tech Stack
* **Language**: Python
* **Libraries**: PyTorch, XGBoost, Scikit-learn, Pandas, NumPy
* **Documentation**: LaTeX
* **Data Source**: University of Michigan PSID/CDS

## 📈 Methodology & Results
The research followed a structured pipeline: **Data Preparation → Parent-Child Matching → Linking Scores to Outcomes → Statistical & ML Modeling.**



### Key Insights:
1.  **Intergenerational Transmission**: Parental numeracy is a strong, continuous predictor of a child’s performance. Children of parents with "perfect" scores (6/6) showed significantly higher average scores.
2.  **Economic Impact**: Stronger childhood numeracy is significantly associated with higher adult income and improved financial resilience.
3.  **Predictive Factors**: Machine learning analysis identified parental income, household expenditure patterns, and educational expectations as the most critical predictors of long-term skill development.

## 👥 Contributors & Mentorship
* **Omar Bin Talib**
* **Aws Alsaedi**
* **Mentor**: Professor Michael Boutros (University of Toronto).

## 🙏 Acknowledgements
This research was supported by the **Data Sciences Institute at the University of Toronto** and the **KAUST Academy**. Special thanks to the PSID and CDS teams for providing the essential data for this study.
