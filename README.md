# FanDuel-Bonus-Optimization-Engine
This machine learning project simulates an end-to-end system for optimizing bonus distribution across FanDuel Sportsbook users. It addresses the business challenge of maximizing ROI on promotional spend by predicting which users will generate the most value from bonuses.
FanDuel allocates millions in promotional bonuses. This model helps:
- Identify the most profitable customer segments
- Predict bonus effectiveness per user
- Allocate bonus spend intelligently
-  egmentation: KMeans clustering segments users based on betting behavior
- Visualization: PCA plots provide interpretable segment analysis
- Modeling**: Random Forest Regressor predicts `bonus_roi`
- Explainability: SHAP TreeExplainer reveals key predictive features
- - Average Bet Amount
- Win Rate
- Bonus Amount / Bonus Used
- Total Deposit
- Days Since Last Bet
- - Python (Pandas, Scikit-learn, SHAP)
- KMeans, PCA, Random Forest
- SHAP Summary Plot for model explainability
- Google Colab / Jupyter Notebook
- - User segment definitions
- Bonus ROI predictions per user
- SHAP visualization for transparency
- Trained model saved as `.pkl`
   Use Case Fit
This project directly addresses responsibilities in FanDuel’s job posting:
 "Lead data science projects that improve bonus spend efficiency and CRM targeting."
Contact
romanwdobczansky@gmail.com  
[linkedin.com/in/roman-w-dobczansky](https://linkedin.com/in/roman-w-dobczansky)
