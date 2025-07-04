# 🎓 Student Internship Success Prediction

This project predicts whether a student will successfully complete an internship program based on their academic profile and application behavior.

## 📌 Objective

To build a classification model that can identify student success in internships using features like department, domain, year, and participation status.

## 📊 Dataset

Since real institutional data is not public, we generated a synthetic dataset of 300 students from MITS using the `Faker` library. Each record includes:

- Department (CSE, ECE, IT, etc.)
- Year (2nd, 3rd, 4th)
- Internship Domain (AI/ML, Web Dev, Data Science, etc.)
- Participation Status (Applied, Completed, etc.)
- Application Date
- Success (binary target)

## 🔍 EDA & Visualizations

We performed complete exploratory analysis:

- Univariate: Domain popularity, participation status
- Bivariate: Domain vs. Success, Department vs. Success
- Multivariate: Heatmaps & time trends

## 🧹 Preprocessing

- Label encoding for categorical variables
- Feature selection
- Train-test split
- Feature scaling (for models like SVM, Logistic Regression)

## 🤖 Models Trained

- Logistic Regression
- Random Forest Classifier ✅ (Best)
- Support Vector Machine (SVM)

## 🏆 Results

| Model               | Accuracy | Precision | Recall |
|---------------------|----------|-----------|--------|
| Logistic Regression | 83%      | 78%       | 68%    |
| Random Forest       | **100%** | **100%**  |**100%**|
| SVM                 | *100%**  | **100%**  |**100%**|

🎯 **Random Forest** and **SVM** were the best model in terms of accuracy and recall.

## ✅ Conclusion

This project demonstrates how data science can be used to analyze student behavior and predict outcomes. It can help colleges/institutions better allocate internship opportunities and support student success.

## 🛠 Tech Stack

- Python (Pandas, Seaborn, Scikit-learn)
- Jupyter Notebook
