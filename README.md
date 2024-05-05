# UAE Rent Prediction

## 1. Objective
Primary objective of this Project is to develop a predictive model that estimates the rental prices in UAE based on the dataset. Aim is to accurately predict the rental price of houses in UAE by using some metrics for evaluation of the model. Metrics that will be used in this project are: R2 Score, MSE (Mean Squared Error), MAE (Mean Absolute Error), and MPE (Mean Percentage Error). This project will use different ML models, ML models that will be used in this project are: Ridge, Lasso, Random Forest, and OLS. After creating models, we will use evaluation metrics to compare those models and select the best one possible. If this project yields a strong result, then it can be used for both realtors who are renting house and customers who wants to rent a house in UAE.

## 2. Problem Statement
In the United Arab Emirates (UAE), particularly in metropolises like Dubai and Abu Dhabi, the high cost of rental housing is increasing the cost of living, affecting both local residents and foreign workers. This situation creates difficulties in finding affordable housing and deepens social inequalities. Machine learning (ML) models can offer innovative solutions to this problem by enabling more transparent and fair determination of rental prices. However, successful implementation of these models can bring challenges such as data quality and integrity, model complexity, and adaptation to market condition changes. ML models can support both property owners and tenants in making informed decisions by analyzing the multidimensional factors affecting rental prices. These models can quickly adapt to market dynamics, creating a structure resistant to sudden changes in rental prices. Consequently, a data-driven, dynamic, and flexible ML-based approach can contribute to creating a more balanced rental ecosystem in the UAE, addressing the problem of rental house prices.

## 3. Dataset Details
Dataet used in this project presents a comprehensive overview of rental property listings across multiple cities in the United Arab Emirates, including Abu Dhabi, Dubai, Sharjah, Ajman, Ras Al Khaimah, Umm Al Quwain, and Al Ain. Compiled from bayut.com.
•	Dataset Name: Dubai Real Estate Goldmine, UAE Rental Market Data
•	Source:  https://www.kaggle.com/datasets/azharsaleem/real-estate-goldmine-dubai-uae-rental-market
•	Features:
•	Address: Full address of the property.
•	Rent: The annual rent price in AED.
•	Beds: Number of bedrooms in the property.
•	Baths: Number of bathrooms in the property.
•	Type: Type of property (e.g., Apartment, Villa, Penthouse).
•	Area_in_sqft: Total area of the property in square feet.
•	Rent_per_sqft: Rent price per square foot, calculated as Rent divided by Area_in_sqft.
•	Rent_category: Categorization of the rent price (Low, Medium, High) based on thresholds.
•	Frequency: Rental payment frequency, which is consistently 'Yearly'.
•	Furnishing: Furnishing status of the property (Furnished, Unfurnished).
•	Purpose: The purpose of the listing, typically 'For Rent'.
•	Posted_date: The date the property was listed for rent.
•	Age_of_listing_in_days: The number of days the listing has been active since it was posted.
•	Location: A more specific location within the city where the property is located.
•	City: City in which the property is situated.
•	Latitude, Longitude: Geographic coordinates of the property.

## 4. Data Preprocessing
Dataset does not contain any missing values, used Label Encoding to encoding the object values to numerical values.
<img width="468" alt="image" src="https://github.com/omerburakguler/UAE-Rent-Prediction/assets/91601087/da727174-dd32-4a25-a454-958d7717bff2">
Distribution of the features.
<img width="468" alt="image" src="https://github.com/omerburakguler/UAE-Rent-Prediction/assets/91601087/4d3c82b1-016e-4ff6-9681-c4534c83aadc">
Correlation map of the features.

## 5. Models
Models Used:
Ridge, Lasso, Random Forest, OLS. All are created with and without hyperparameter tuning with using GridSearchCV.
Results:
<img width="901" alt="Screenshot 2024-05-05 at 17 34 26" src="https://github.com/omerburakguler/UAE-Rent-Prediction/assets/91601087/f2e2841f-2967-4328-a3d6-8aa25c19e2d7">

Results Graphically:
<img width="468" alt="image" src="https://github.com/omerburakguler/UAE-Rent-Prediction/assets/91601087/92997aa8-3b18-4e41-ae5d-64b54ebf4c38">
<img width="468" alt="image" src="https://github.com/omerburakguler/UAE-Rent-Prediction/assets/91601087/cd7ade86-94e5-4f77-a30d-01af7fe7da06">
<img width="468" alt="image" src="https://github.com/omerburakguler/UAE-Rent-Prediction/assets/91601087/fd1e41c5-45f5-48f0-ab6d-63c9899cf0e6">
<img width="468" alt="image" src="https://github.com/omerburakguler/UAE-Rent-Prediction/assets/91601087/0947dccb-e5c9-4fd6-8a30-875e291c0bc7">





