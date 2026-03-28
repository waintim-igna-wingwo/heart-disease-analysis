
🫀 Heart Disease Risk Analysis – Machine Learning Project
📌 Overview
This project focuses on building a Machine Learning model to predict the risk of heart disease using patient medical data from Kaggle. The goal is to analyze health-related features and train a model that can classify whether a patient is likely to have heart disease or not.
📊 Dataset
The dataset used for this project was obtained from Kaggle and contains various medical attributes such as:
Age
Sex
Chest pain type (cp)
Resting blood pressure
Cholesterol level
Fasting blood sugar
Resting ECG results
Maximum heart rate achieved
Exercise-induced angina
ST depression and slope
🧹 Data Preprocessing
To prepare the data for machine learning:
Handled missing values (if any)
Cleaned string/object columns using .str.lower().str.strip()
Converted categorical variables using One-Hot Encoding (pd.get_dummies)
Ensured dataset consistency for training
🤖 Model Building
Split the dataset into training and testing sets
Trained a classification model (Logistic Regression / other ML models tested)
Model learned patterns between patient health features and heart disease risk
📈 Evaluation
Model performance evaluated using accuracy score
Achieved an accuracy of approximately 0.83 (83%)
Results show the model performs well in predicting heart disease risk based on input features
🔍 Key Insights
Certain features like chest pain type and maximum heart rate strongly influence prediction
Proper data cleaning significantly improved model performance
Encoding categorical data was crucial for training accuracy
🚀 Tools & Technologies
Python 🐍
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn (for visualization)
🎯 Conclusion
This project demonstrates how machine learning can be used in healthcare to assist in early detection of heart disease risk. With further improvements and tuning, the model can be made even more accurate and reliable for real-world applications.
👨‍💻 Author
Waintim igna wingwo
Aspiring Machine Learning & AI Engineer
