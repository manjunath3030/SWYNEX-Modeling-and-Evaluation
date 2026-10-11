SWYNEX-Modeling-and-Evaluation
Task 3 — Modeling and Evaluation | Data Science Internship at SWYNEX Technologies

🎯 Objective
Build a baseline machine learning model to predict Titanic passenger survival and evaluate its performance.

🛠️ Process
Loaded the cleaned dataset from Task 1
Converted text to numbers (Sex → 0/1, Embarked → one-hot encoding)
Selected 8 features based on Task 2 EDA insights
Split data: 80% training / 20% testing
Trained baseline model: Logistic Regression
Evaluated with accuracy, confusion matrix, classification report
Compared against Random Forest
Analyzed feature importance
📊 Results
Baseline (Logistic Regression): ~80% accuracy
Random Forest comparison: ~81%
Most influential features: Sex, Pclass, Fare
💡 Key Takeaway
The model independently confirmed my Task 2 EDA findings —gender, class, and fare were the strongest survival factors.

💻 Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Google Colab
