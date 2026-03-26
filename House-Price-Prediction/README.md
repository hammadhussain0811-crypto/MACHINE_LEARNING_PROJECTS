#  House Price Prediction using Machine Learning

##  Project Overview

This project aims to predict house prices using Machine Learning regression models. The dataset contains various features such as income, house age, number of rooms, and population, which are used to estimate house prices.



##  Dataset

* Dataset: USA Housing Dataset
* Features:

  * Avg. Area Income
  * Avg. Area House Age
  * Avg. Area Number of Rooms
  * Avg. Area Number of Bedrooms
  * Area Population
* Target variable: **Price (House Price)**
* Note: The **Address** column was removed as it is non-numeric and not useful for prediction.



## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost



##  Steps Performed

### 1. Data Preprocessing

* Loaded dataset from CSV file
* Checked for missing values
* Dropped irrelevant column (Address)
* Prepared features and target variables



### 2. Exploratory Data Analysis (EDA)

* Used pairplot to understand relationships between features
* Generated correlation heatmap
* Analyzed feature distributions



### 3. Model Building

Trained multiple regression models:

* Linear Regression
* XGBoost Regressor



### 4. Model Evaluation

Used the following evaluation metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score



## Results

| Model             | MAE     | RMSE     |Performance      |
| Linear Regression | ~82,000 | ~102,000 |  Best           |
| XGBoost           | ~91,000 | ~107,000 |  Slightly worse |



##  Conclusion

* Linear Regression outperformed XGBoost on this dataset.
* The dataset shows a mostly linear relationship between features and house prices.
* The model achieved low prediction error and strong predictive performance.
* Residual analysis confirmed that the model is unbiased and statistically reliable.


##  Project Structure


House-Price-Prediction/
│── House_Price_Prediction.ipynb
│── README.md
│── requirements.txt




##  Key Learnings

* Understanding regression techniques
* Importance of Exploratory Data Analysis (EDA)
* Model comparison and evaluation
* Selecting the most suitable model for a dataset


## BY-Hammad Hussain


