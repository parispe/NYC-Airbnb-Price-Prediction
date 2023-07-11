# NYC-Airbnb-Price-Prediction
Created a price prediction machine learning model using Skit-Learn for NYC Airbnb Market. Using data obtained from
Insider Airbnb, specifically listing data. I thought it would be an interesting project to get more familiar with exploring, visualizing, and building machine learning models.

Data:
- Shape and Base Map obtained from NYC Open Data
- Listing Data obtained from Insider Airbnb

Exploratory Data Analysis: 
- Using Pandas to explore the dataset
- Visualization of the dataset with Matplotlib, Seaborn, Geopandas
- Identifying the correlation between price and features

Data Cleaning
- Dropping unnecessary columns
- Filling in missing values

Machine Learning
- Conducted Feature engineering with OneHotEncoder and StandardScaler
  - Transforming categorical values into numerical ones for the training dataset
  - Standardized numerical values
  - Preprocess training set for models
- Partition Dataset into Train, Validation, and Test sets
  - Verifying the shape of training and test sets
- Using different ML models and implementing evaluation metrics
  - Used Root Mean Square Error & R2
  - Visualizing predicted & actual values from validation sets
  
