# Car Price Prediction Using Regression Models

## Project Overview
This project aims to predict car prices using multiple regression models. A Chinese automobile company wants to enter the US market and needs insights into car pricing dynamics. By analyzing various factors affecting car prices, this project helps in understanding the pricing strategies for the American market.

## Dataset
The dataset consists of various car features and their respective prices. It includes numerical and categorical variables that impact pricing.

Dataset Link: [Download Here](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link)

## Key Objectives
- Perform data preprocessing and handle missing values.
- Implement five regression models:
  1. Linear Regression
  2. Decision Tree Regressor
  3. Random Forest Regressor
  4. Gradient Boosting Regressor
  5. Support Vector Regressor
- Evaluate models using R² score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
- Identify key features affecting car prices through feature importance analysis.
- Perform hyperparameter tuning to improve model performance.

## Steps Implemented
1. **Data Preprocessing:**
   - Handle missing values.
   - Convert categorical variables to numerical.
   - Scale numerical features for better model performance.
   - 
2. **Model Implementation:**
   - Train and evaluate regression models.
3. **Feature Importance Analysis:**
   - Identify significant variables that influence car prices.
4. **Hyperparameter Tuning:**
   - Optimize model parameters using GridSearchCV.

## Results
- The project compares the performance of multiple regression models.
- The best-performing model is selected based on evaluation metrics.
- The feature importance analysis highlights key factors affecting car prices.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn

## How to Run the Project
1. Clone the repository.
2. Install required dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to execute the analysis and train the models.

## Conclusion
This project successfully predicts car prices using regression models and identifies the key factors influencing them. The comparative analysis of multiple models helps in selecting the best approach for accurate predictions. The insights gained can assist automobile companies in making strategic pricing decisions for new market entry.

