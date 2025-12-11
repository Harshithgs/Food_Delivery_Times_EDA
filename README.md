# 📌 README — Food Delivery Time EDA Project

## 📖 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a Food Delivery Time dataset to understand the factors that influence delivery duration. The analysis includes data cleaning, handling missing values, visual exploration, and preparing the dataset for future machine learning applications.

---

## 🎯 Objectives
- Understand dataset structure  
- Identify patterns affecting delivery time  
- Handle missing values appropriately  
- Explore relationships between features  
- Prepare clean data for modeling  

---

## 📂 Dataset
**File:** `Food_Delivery_Times.csv`

Contains fields such as:
- Order ID  
- Delivery Time  
- Distance  
- Traffic Level  
- Weather  
- Vehicle Type  
- Time of Day  
- Delivery Person Ratings  
- Preparation Time  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Steps Performed

### 1. Importing Libraries
Loaded necessary libraries for data manipulation and visualization.

### 2. Loading the Dataset
Read CSV file and previewed the dataset.

### 3. Basic Exploration
- Inspected data types using `df.info()`  
- Viewed statistical summary with `df.describe()`  
- Checked missing values using `df.isnull().sum()`  

### 4. Data Cleaning

#### a. Creating a Clean Copy
A clean dataset (`df_clean`) was created to preserve the original data.

#### b. Converting Data Types
`Order_ID` was converted to string because it is an identifier, not a numeric variable.

#### c. Handling Missing Values (Imputation)
- **Numerical columns** → filled with **median**
- **Categorical columns** → filled with **mode**

---

## 📊 Exploratory Data Analysis (EDA)

### Univariate Analysis
- Histograms for numerical features  
- Count plots for categorical variables  
- Boxplots for detecting outliers  

### Bivariate Analysis
Explored how Delivery Time changes with:
- Distance  
- Traffic  
- Weather  
- Vehicle Type  
- Preparation Time  
- Time of Day  

### Correlation Analysis
Heatmaps were used to understand relationships between numeric variables.

---

## 🧼 Cleaned Dataset
The cleaned dataset is saved as:
`cleaned_food_delivery.csv`

