# 💻 Laptop Price Prediction   

## 📌 Project Overview  
This project aims to predict the price of laptops based on their specifications such as **brand, processor, RAM, storage, screen size, GPU, and other key features**. The model helps users estimate laptop prices, making it useful for buyers, sellers, and e-commerce platforms.  

## 📊 Dataset    
- **Features:**  
  - `Brand` (e.g., Dell, HP, Apple)  
  - `Processor` (e.g., Intel i5, Ryzen 7)  
  - `RAM` (in GB)  
  - `Storage` (HDD/SSD size)  
  - `GPU` (Graphics Card)  
  - `Screen Size`  
  - `Resolution`  
  - `Operating System`  
  - `Weight`  
  - `Touchscreen` (Yes/No)  
  - **Target Variable:** `Price (in USD or INR)`  

## 🛠️ Tech Stack  
- **Python**   
- **Pandas, NumPy** for data preprocessing  
- **Matplotlib, Seaborn** for EDA  
- **Scikit-Learn** for model building    
- **Pickle** for model saving  

## 📈 Data Preprocessing  
- Handling missing values  
- Encoding categorical features  
- Feature scaling  
- Outlier detection  

## 🤖 Model Building  
- **Algorithms Tried:**  
  - Linear Regression  
  - Random Forest  
  - XGBoost  
  - Decision Tree    
- **Performance Metrics:** RMSE, R² Score  
