# 📊 Exploratory Data Analysis (EDA) on Churn Prediction Dataset

This project is part of my **Excelerate Internship Program**, where I performed **Exploratory Data Analysis (EDA)** on a **Churn Prediction Dataset** to uncover key insights and prepare the data for machine learning tasks.

---

## 📌 Project Overview
- 📂 **Dataset**: Customer Churn Dataset  
- 🎯 **Objective**: Perform in-depth data exploration, visualization, and preprocessing to identify factors that influence customer churn.  
- 🧠 **Goal**: Understand the data distribution, handle missing values, detect outliers, and prepare the dataset for predictive modeling.

---
## Project Tasks
<img width="1324" height="503" alt="Screenshot 2025-11-11 005237" src="https://github.com/user-attachments/assets/3946d85e-c157-4cc3-9ad0-ede589e9e809" />
<img width="1323" height="515" alt="Screenshot 2025-11-11 005317" src="https://github.com/user-attachments/assets/60050ed2-2e59-45a6-a11e-1042313eef42" />


## ⚙️ Tools & Libraries Used
- **Programming Language:** Python  
- **Libraries:**
  - `pandas` → Data manipulation and preprocessing  
  - `numpy` → Numerical operations  
  - `matplotlib` & `seaborn` → Data visualization  
  - `sklearn` → Basic preprocessing utilities  

---

## 🔍 EDA Process

### Step 1: Import Libraries and Dataset
- Loaded the dataset using **pandas**
- Displayed initial rows using `df.head()`
- Checked dataset dimensions with `df.shape()`

### Step 2: Data Inspection
- Used `df.info()` and `df.describe()` to understand column data types and statistics  
- Identified missing and null values  
- Checked for duplicate entries and removed them if necessary  

### Step 3: Data Cleaning
- Filled missing numerical and categorical values using appropriate methods (`mean`, `mode`, `median`)  
- Handled inconsistent or incorrect data entries  
- Encoded categorical columns for better analysis  

### Step 4: Data Visualization
- Created **histograms** and **count plots** to analyze numerical and categorical distributions  
- Used **heatmaps** to visualize correlations between features  
- Visualized **churn vs features** using bar plots and boxplots  

### Step 5: Outlier Detection
- Detected outliers using **boxplots** and **IQR method**  
- Treated or removed outliers where necessary  

### Step 6: Feature Relationships
- Explored relationships between churn and variables like age, tenure, balance, and product usage  
- Used pair plots and correlation matrices for deeper insights  

### Step 7: Summary of Insights
- Identified top features correlated with churn  
- Discovered trends showing which customer segments are most likely to churn  

---

## 📊 Key Insights
- Customers with lower tenure or balance tend to churn more frequently.  
- Higher product usage and engagement reduce churn probability.  
- Certain demographic and financial features strongly influence customer retention.  

---
## 🎯 Use Cases  
- 📚 Educational use for learning **Data Cleaning & Preprocessing**  
- 🧠 Practice project for **Data Analytics & EDA**  
- 📊 Useful for **survey-based research & reporting**  
- 📁 Portfolio project for **job interviews**  

---

## 👨‍💻 Author
     Zohaib Sattar
- 📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
- 🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar-5680ab2a5/)  

---

## ⭐ Support the Project
If this project helped you learn or saved your time, please ⭐ star the repo and share it.  
It keeps the motivation high for open-source contributors! 🚀
