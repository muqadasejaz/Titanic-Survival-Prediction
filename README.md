# 🚢 Titanic Survival Prediction

A machine learning project that predicts whether a passenger would survive the Titanic disaster based on various features using a **Decision Tree Classifier**.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Overview

This project applies data science and machine learning techniques to predict survival outcomes for Titanic passengers based on demographic and ticket information.  
It follows a full machine learning pipeline , from data preprocessing, visualization, feature engineering, model training, to real-time prediction.

The model is trained on the famous Titanic dataset from Kaggle and achieves an accuracy of **76%** using a Decision Tree Classifier.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features

- ✔️ Data loading and exploratory analysis
  
- ✔️ Handling missing values and duplicate entries
  
- ✔️ Dropping unnecessary columns that do not contribute to the model
   
- ✔️ Outlier detection and standardization to normalize data distribution
  
- ✔️ Visualizing patterns and distributions with Seaborn and Matplotlib
  
- ✔️ Label Encoding for categorical variables (`Sex`, `Embarked`)
  
- ✔️ Model training using Decision Tree Classifier
  
- ✔️ Accuracy evaluation using test data
  
- ✔️ Prediction on new data
  
- ✔️ Prediction results include both class label and probability

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  ## 🛠️ Tools & Technologies

- **Language**: Python
  
- **Data Manipulation**: Pandas, NumPy
  
- **Visualization**: Matplotlib, Seaborn
  
- **Machine Learning**: DecisionTreeClassifier

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Dataset

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
   
- The dataset contains information for over 800 passengers and includes:
  - `PassengerId`: Unique identifier
  - `Pclass`: Passenger class (1st, 2nd, 3rd)
  - `Sex`: Gender of the passenger
  - `Age`: Age in years
  - `SibSp`: Number of siblings or spouses aboard
  - `Parch`: Number of parents or children aboard
  - `Fare`: Ticket fare
  - `Embarked`: Port of Embarkation (C, Q, S)
  - `Survived`: Target column (0 = Did not survive, 1 = Survived)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Results

- 🔍 Model Used: **Decision Tree Classifier**
- 🎯 Accuracy: **76%**
- ✅ Performance checked using accuracy score and confusion matrix
- 📈 Balanced precision and recall across survival and non-survival predictions

- Data Visualization:
- Survival Rate by Gender

  <img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/e0934d6e-f5fc-4727-9355-fe6d5c092911" />

- Survival Rate by Passenger Class

  <img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/3909b357-4157-41b8-b62c-62fee5fce4ca" />

- Survival Rate by Age

  <img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/2d0c1916-db7e-461f-86ef-c9b4da2492e9" />

- Embarked Distribution

  <img width="581" height="463" alt="image" src="https://github.com/user-attachments/assets/0fc08879-0d0c-43b8-b04a-c861a635de79" />

- Confusion Matrix:

  <img width="514" height="402" alt="image" src="https://github.com/user-attachments/assets/4ad8dfd1-11fb-4c4c-b7e8-f7737fcbe268" />

- Classification Report:

  <img width="1081" height="301" alt="Classification_report" src="https://github.com/user-attachments/assets/687a2644-538c-4e0f-a248-a4862a6d7f0b" />

- Predictions:

  <img width="811" height="236" alt="predictions" src="https://github.com/user-attachments/assets/4f4affcb-e12c-423b-9c78-4df3d15669b1" />

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📚 References

- https://www.kaggle.com/datasets/yasserh/titanic-dataset
  
- https://www.geeksforgeeks.org/machine-learning/titanic-survival-prediction-using-ml/
  
- https://www.analyticsvidhya.com/blog/2021/07/titanic-survival-prediction-using-machine-learning/
  
- https://medium.com/@xrpapak/titanic-survival-prediction-a-complete-data-science-project-14fef6a3a749
  

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 👤 Author

Muqadas Ejaz

BS Computer Science (AI Specialization)

Machine Learning & Computer Vision Enthusiast

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).
