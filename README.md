# Medical Insurance Cost Prediction

## 1. Introduction
This project predicts medical insurance charges using machine learning regression algorithms. The project is implemented in Python using Google Colab.

## 2. Objective
- Load and explore the medical insurance dataset.
- Perform data cleaning and preprocessing.
- Visualize data using graphs.
- Calculate correlation and covariance.
- Train and test different regression models.
- Compare model performance and select the best model.
- Save the best model and predict insurance charges for new inputs.

## 3. Dataset
The dataset used is `insurance.csv`.

It contains the following columns:
- `age` – Age of the person
- `sex` – Gender
- `bmi` – Body Mass Index
- `children` – Number of children
- `smoker` – Smoking status
- `region` – Residential region
- `charges` – Medical insurance charges (target variable)

## 4. Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 5. Machine Learning Models
The following regression models are implemented and compared:
1. Multiple Linear Regression
2. Ridge Regression
3. Lasso Regression
4. Decision Tree Regression
5. Random Forest Regression

## 6. Project Workflow
1. Load the dataset.
2. Display dataset information and check missing values and duplicates.
3. Perform Exploratory Data Analysis (EDA).
4. Clean the dataset and encode categorical variables.
5. Calculate correlation and covariance.
6. Split the data into training and testing sets.
7. Train the five regression models.
8. Evaluate models using R² Score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
9. Select the best-performing model.
10. Save the model using Joblib.
11. Predict insurance charges for new inputs.

## 7. Evaluation Metrics
- **R² Score:** Measures how well the model explains variations in the target.
- **MSE:** Measures the average squared prediction error.
- **MAE:** Measures the average absolute prediction error.

## 8. How to Run
1. Open the notebook in Google Colab.
2. Upload `insurance.csv`.
3. Run the notebook cells in order.
4. Review the model comparison and best model.
5. Enter new input values to predict insurance charges.

## 9. Conclusion
This project demonstrates how machine learning regression algorithms can be used to predict medical insurance charges. The models are compared using evaluation metrics to identify the best-performing model.

## 10. Author
Student Project – Practical 8
