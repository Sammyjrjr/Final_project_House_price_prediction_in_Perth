# Final_project_house_price_prediction_in_Perth

Housing Price Analysis and Prediction

Final Bootcamp Project: Ironhack
Date: 21 Jan 2023


Process
Trello: Trello board for sharing and keeping the project organized and safe.
EDA: Assessed the dataset for cleaning and explored them using Sweetviz, Seaborn, Matplotlib and ArcGIS pro.
Data cleaning and wrangling: Used date of building, sold and renovation to consider the age and renovation. Considered duplicated houses and dropped them keeping the latest one and dropped the one house with 33 bathrooms because it did not make sense considering the other given features.
Preprocessing: Normalized the data using Standard Scaler. Used Grid Search CV to identify the best parameters for models.
Machine Learning: Trained automated machine learning models and corresponding R2 for them. The models are: Linear Regression, SGD model, K Neighbours Regressor, Decision Tree Regressor, and Random Forest Regressor. Based on the R2 of the train and test sets "Random Forest Regressor" has been chosen for the final prediction.
Streamlit: Used stremlit app to give price prediction for any given feature values.
Canva: Used Canva for presentation preparation.


Methods and Tools used
Pandas
Numpy
Seaborn
Plotly
scikit-learn
math
Tableau
Predictive models such as:
Linear Regression
Random Forest
KNeighbors
Ridge
Lasso



