# Crop_yield_prediction
![Screenshot 2025-03-09 010013](https://github.com/user-attachments/assets/5e3c28db-5fd0-42da-b5f3-2acdf02fe1be)

### Overview of the File: **Crop Yield Prediction**  

The document is a data science project focused on predicting crop yield using machine learning models. Here’s a breakdown of its key components:  

#### **1. Dataset Overview:**  
The dataset includes features such as:  
- **Rainfall (mm)**  
- **Temperature (°C)**  
- **Fertilizer (kg)**  
- **Nitrogen (N), Phosphorus (P), Potassium (K)**  
- **Yield (Q/acre) (Target Variable)**  

#### **2. Data Preprocessing:**  
- Checked for data types and missing values.  
- Fixed data type issues (e.g., converting temperature from object to float).  
- Replaced missing values with the median.  

#### **3. Exploratory Data Analysis (EDA):**  
- **Distribution Analysis:** Histograms and scatter plots were used to analyze rainfall, temperature, fertilizers, and macronutrients.  
- **Clustering Observations:** The data shows two distinct groups, suggesting two different types of crops in the dataset.  
- **Correlation Matrix:** Analyzed relationships between different features and yield.  

#### **4. Machine Learning Models Used:**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**  

##### **Model Training & Hyperparameter Tuning:**  
- Used **GridSearchCV** to optimize model parameters.  
- The **Random Forest Regressor** performed better with an **R² score of 0.802**, compared to **0.77** for the Decision Tree model.  

#### **5. Model Evaluation:**  
- Used **Mean Squared Error (MSE)**, **Mean Absolute Error (MAE)**, and **R² score** for performance comparison.  
- The **Random Forest model was more accurate.**  

#### **6. Feature Importance:**  
- **Temperature** was the most important feature in predicting crop yield.  
- Rainfall also played a significant role, while macronutrients had relatively lower importance.  

#### **7. Conclusion:**  
- The dataset appears to contain **two types of crops**, confirmed by clusters in rainfall and temperature distributions.  
- **Random Forest Regressor outperformed Decision Tree Regressor.**  
- **Temperature and rainfall were the most influential features for predicting crop yield.**  


