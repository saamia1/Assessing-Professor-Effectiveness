# 📊 Assessing Professor Effectiveness (APE)

This capstone project analyzes **90K+ RateMyProfessor records** to evaluate patterns in how students rate professors and to uncover potential **gender bias** in teaching evaluations. The study applies statistical, analytical, and machine learning techniques to assess factors influencing professor effectiveness.

## 🔍 Project Overview
- Investigated **gender differences** in average ratings, difficulty scores, and qualitative tags (e.g., “tough grader,” “caring,” “inspirational”).
- Conducted **hypothesis testing**, computed **effect sizes (Cliff’s Delta)**, and derived **confidence intervals** to assess statistical significance and impact strength.
- Built **multiple regression models** to predict average ratings and difficulty levels.
- Developed a **classification model** to predict whether a professor receives a “hot pepper” icon, addressing **class imbalance** and evaluating model performance with **ROC-AUC**.
- Applied **data cleaning**, normalization of tag frequencies, and outlier handling to ensure robust results.

## 🧠 Key Insights
- Explored relationships between student sentiment, teaching difficulty, and overall ratings.
- Found statistically significant differences linked to gender and teaching style tags, with measurable **effect sizes** indicating impact magnitude.
- Compared predictive power across numerical, qualitative, and tag-based features to identify key drivers of perceived effectiveness.

## 🛠️ Tools & Technologies
- **Python:** pandas, NumPy, scikit-learn, matplotlib, seaborn  
- **Statistical Analysis:** Hypothesis Testing, Confidence Intervals, Effect Size (Cliff’s Delta)  
- **Modeling:** Regression & Classification (Linear Regression, Logistic Regression)  
- **Visualization:** Data plots, trend analysis, and dashboard-ready insights  
- **BI Tools:** Tableau, Power BI  

## 📁 Dataset
The dataset includes information on **89,893 professors**, combining numerical, qualitative, and tag-based attributes from RateMyProfessor.  
Key features include:
- Average rating, average difficulty, number of ratings, and gender  
- Teaching-related tags such as “Tough grader,” “Inspirational,” “Caring,” etc.  
- Qualitative attributes like university, major, and U.S. state  

## 📈 Results Summary
- Found measurable **gender differences** in both ratings and tag distributions  
- Identified **most predictive factors** influencing professor ratings and difficulty  
- Achieved reliable model performance with interpretable and statistically validated outcomes  
