# UberRide: Unlocking Ride Patterns & Predictions

This project analyzes Uber trip data from **April 2014 to June 2015** to predict ride demand trends. It involves **data preprocessing, exploratory data analysis (EDA), feature engineering, time-series modeling** and **ensemble learning models (XGBoost & GBTR)** for prediction.

## Features:

- **Large-Scale Data Handling**: Optimized memory usage to efficiently process large Uber datasets.
- **Exploratory Data Analysis (EDA)**: Trends, demand fluctuations and seasonal patterns.  
- **Feature Engineering**: Created time-based features (hour, day, month, holidays, rush hours, etc.).
- **Time-Series Decomposition**: Trend, seasonality and residual analysis.
- **Predictive Modeling**:
  - XGBoost (Extreme Gradient Boosting)
  - GBTR (Gradient Boosting Trees Regressor)
  - Ensemble Model (weighted combination of XGBoost & GBTR)
- **Model Evaluation**: Metrics include MAPE, RMSE, R², Adjusted R² and MAE.
- **Power BI Dashboard** for interactive visualizations.

## Tools and Technologies Used:

- **Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost, Statsmodels)**
- **Jupyter Notebook** for analysis
- **Power BI** (for visualization)
  
## Datasets:

- **Uber Trips (April - September 2014)** (`uber-raw-data-aprsep-14.csv`)
- **Uber Trips (January - June 2015)** (`uber-raw-data-janjune-15.csv`)

## Workflow:

- **Data Collection**     
  Gather raw Uber trip data. 
- **Data Preprocessing**      
  Handle missing values, feature engineering.  
- **Exploratory Data Analysis (EDA)**     
  Trends, seasonality, visualization.
- **Feature Engineering**     
  Add weather, holidays, rush hour effects.  
- **Model Building**    
  Train XGBoost & GBRT models. 
- **Evaluation**    
  Compare models using MAPE, RMSE, R² metrics. 
- **Deployment**    
  Create a Power BI Dashboard.

## Results & Insights: 

- The **demand for Uber rides fluctuates** with peak hours during rush times (morning and evening).
- The **trip frequency is significantly lower on holidays**.
- **XGBoost performed best** among the models, but an **ensemble model gave the most balanced predictions**.
- **MAPE Score:** _Low error rates suggest strong predictive performance._

## Future Enhancements: 
- **Add real-time Uber trip data** for live forecasting.
- **Integrate weather data** to analyze its effect on ride demand.
- **Deploy the model using Streamlit** for interactive visualization.

## Contact:     

For any questions or collaboration, feel free to reach out!                                 
Github- https://github.com/febisarju
