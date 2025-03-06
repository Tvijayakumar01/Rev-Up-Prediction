🚗 Used Car Price Prediction Using Machine Learning
📌 Overview
Determining the right price for a used car is a critical challenge for dealerships, sellers, and buyers. Pricing a car too high can drive away buyers, while pricing it too low results in financial loss. Traditional methods rely on manual estimation, which often leads to inaccurate pricing.

This project leverages machine learning to predict the fair market price of a used car based on its specifications. The model analyzes key features such as engine size, horsepower, fuel type, brand, and car body type to ensure accurate, data-driven pricing.

This predictive system can help:
✅ Car Dealers & Online Platforms – Optimize car pricing strategies.
✅ Buyers & Sellers – Ensure fair pricing for used vehicles.
✅ Insurance & Financial Institutions – Assess vehicle values for loans and claims.

❓ Problem Statement
Car pricing is influenced by multiple factors, making it difficult to determine the true market value. This project aims to answer:

Can we predict a used car's price accurately using machine learning?
Which factors influence car prices the most?
How can AI improve price transparency in the automotive industry?
Using a dataset with 205 used cars and 26 attributes, the model examines key factors like engine power, weight, fuel efficiency, and market trends to estimate prices.

📊 Dataset Overview
Total Records: 205 Used Cars
Number of Features: 26
Target Variable: Price (Continuous numerical value)
Key Features Considered:
✔ Engine Performance: Engine size, horsepower, fuel type.
✔ Vehicle Attributes: Curb weight, wheelbase, car body type.
✔ Market Factors: Brand, drive wheels, depreciation trends.

Why This Dataset?
✅ Comprehensive data – Covers both technical and economic factors influencing car price.
✅ Real-world applicability – Enables reliable pricing models for sellers and buyers.
✅ No missing values – Ensures efficient data preprocessing.

🔍 Key Findings from Data Analysis
During Exploratory Data Analysis (EDA), we identified important trends:

✔ Engine Size, Horsepower, and Curb Weight have the strongest correlation with price.
✔ SUVs and Four-Wheel-Drive (4WD) Vehicles hold higher resale value.
✔ Luxury Brands depreciate slower, maintaining higher market prices.
✔ Fuel Type Impact – Diesel cars are often priced higher than petrol cars.

📌 Outlier Handling & Data Cleaning:
✅ Removed extreme values in price, horsepower, and engine size using the Interquartile Range (IQR) method.
✅ Feature Correlation Analysis – Removed redundant features to prevent model bias.

🛠 Feature Engineering – Improving the Model
To enhance model accuracy and efficiency, we applied advanced feature engineering techniques:

✅ One-Hot Encoding: Converted categorical data (e.g., fuel type, car body) into numerical format.
✅ Feature Scaling: Applied MinMax Scaling to normalize numerical values (e.g., engine size, curb weight).
✅ Feature Selection: Used Variance Thresholding to eliminate low-impact features.

📌 Why do this?
✔ Ensures consistency across different car models.
✔ Prevents misleading price estimations by focusing on relevant features.

🏆 Model Selection – Finding the Best Approach
We tested multiple machine learning models to identify the best one for used car price prediction:

Model	R² Score	Mean Squared Error (MSE)
Linear Regression	0.85	High
Decision Tree	0.92	Moderate
Random Forest (Best Model) ✅	0.96	Lowest (Best)
🚀 Why Random Forest?
✅ Best Accuracy (96%) – Outperforms other models.
✅ Handles Non-Linearity – Captures complex relationships in car pricing.
✅ Feature Importance Insights – Identifies engine size, horsepower, and fuel type as the most influential factors.

🏢 Real-World Business Applications
Our AI-powered car price prediction model can be used in multiple sectors:

✔ Car Dealerships – Optimize pricing strategies based on real-time data.
✔ Online Car Sales Platforms (Carvana, AutoTrader, etc.) – Automate price recommendations.
✔ Insurance Companies – Assess vehicle values for insurance claims and loans.
✔ Private Buyers & Sellers – Determine a fair market price before purchasing or selling a used car.

🚀 Potential Benefits:
✅ Fair & Transparent Pricing – Prevents overpricing or undervaluation.
✅ Improved Decision-Making – Helps businesses and consumers make informed choices.
✅ Automation – Reduces manual pricing errors with data-driven insights.

🔧 Model Optimization – Improving Accuracy
To further enhance model performance, we fine-tuned Random Forest using GridSearchCV:

📌 Best Parameters Found:

n_estimators=150 (Number of trees)
max_depth=10 (Tree depth)
min_samples_split=4 (Minimum samples per split)
✅ Results: Increased prediction accuracy by 5%! 🚀

🏆 Final Takeaway
"This project showcases how AI and machine learning can revolutionize pricing strategies in the used car market. By leveraging data science, we can bring transparency, efficiency, and fairness to car buying and selling." 🚀

Key Achievements:
✔ Built an accurate and reliable pricing model.
✔ Applied advanced machine learning techniques for price prediction.
✔ Demonstrated real-world business value for dealerships, buyers, and insurance firms.
