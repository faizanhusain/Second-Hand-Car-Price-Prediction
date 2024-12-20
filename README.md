# Second-Hand-Car-Price-Prediction:
The objective of the "Second-hand Car Price Prediction" project is to develop a machine learning model capable of accurately predicting the price of second-hand cars based on various features that influence the pricing of used cars, such as brand, model, year, mileage, fuel type, and other relevant specifications of the vehicles.
## Motivation:
Determining whether a used car is priced fairly when browsing online listings can be challenging. Numerous factors, such as mileage, make, model, year, and condition, can significantly affect a car's true value. For sellers, pricing a used car accurately presents a similar dilemma. To address this challenge, the goal is to leverage machine learning algorithms to create predictive models that estimate used car prices based on available data.
## Tools Used:
- Programming Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- IDE/Environment: Jupyter Notebook
## Dataset Details:
- Source: Kaggle
- Number of Records: 6018
- Number of Features: 11
- ### Key Attributes:
  - **Numerical:** Mileage, Engine Capacity, Year of Manufacture
  - **Categorical:** Car Brand, Fuel Type, Transmission
  - **Target Variable:** Price
 # Methodology
 1) ## Exploratory Data Analysis (EDA):
    - Identified key features driving car prices.
    - Highlighted trends such as:
      - Cars from premium brands generally command higher prices.
      - Older cars tend to have lower prices due to depreciation.
      - Fuel efficiency significantly affects price perception.
  2) ## Feature Engineering:
     - Categorical variables were encoded using techniques like one-hot encoding.
     - Numerical variables were scaled to improve model efficiency
     - New features, such as age of the car and fuel efficiency index, were created to enhance prediction accuracy.
  3) ## Model Development and Tuning:
     - **Baseline Models:** Linear Regression and Decision Trees.
     - **Advanced Models:** Random Forest, Gradient Boosting, and XGBoost.
     - **Hyperparameter tuning** using GridSearchCV to optimize performance.
  4) ## Model Evaluation:
     - Performance metrics include:
       - R² Score: Measures how well the model explains the variance in prices.
       - MAE: Quantifies the average error in predicted prices.
       - RMSE: Emphasizes larger prediction errors for better interpretability.
#  Results and Findings:
## Key Observations:
![download](https://github.com/user-attachments/assets/b868707f-150c-4713-950a-22dc655d8875)
### 1) Top Features:
- Year: This feature is the most important, indicating that the age of the car significantly affects its price.
- Power: The car's power (likely engine power in horsepower) is the second most impactful factor.
- Engine: The engine's specifications also strongly influence price predictions.
- Brand (Maruti, Mercedes-Benz, BMW, etc.): Certain car brands play a notable role in determining the price, with brands like Maruti and Mercedes-Benz being
  highly impactful.
### 2)  Moderately Important Features:
- Features like Transmission_Manual, Fuel Type (Diesel), and specific brands (e.g., Hyundai, Porsche) have moderate importance.
- These features highlight customer preferences and technical specifications affecting second-hand car pricing.
### 3) Less Important Features:
- Features such as Mileage, Seats, and less popular brands (e.g., Renault, Nissan) have minimal contributions.
- Location-specific features (e.g., Location_Kochi, Location_Kolkata) are less impactful.
## Insights:
- The chart provides a clear understanding of which features are most important for predicting second-hand car prices.
- The results could be used to refine the model further by focusing on high-importance features or improving data quality for less impactful ones.
## Top Performers:
![download](https://github.com/user-attachments/assets/7de155a1-2179-43c7-8a06-d55f0d00eb7c)
 - Optimized Gradient Boosting Regressor and Optimized XGB Regressor exhibit the highest R² scores, suggesting they are the most accurate models in this comparison.
 - Deep Neural Network and XG Boost also have strong performances, ranking just below the top models.
