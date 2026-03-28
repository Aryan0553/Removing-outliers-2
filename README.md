# Placement Data Analysis & Outlier Detection

This project performs **data analysis and outlier detection** on a placement dataset using Python.  
It visualizes CGPA and placement exam marks and applies statistical techniques like **IQR (Interquartile Range)** to detect and handle outliers.

## 📊 Features
- Data loading using **Pandas**
- Data exploration and summary statistics
- Visualization using **Matplotlib & Seaborn**
- Distribution plots and boxplots
- Outlier detection using **IQR method**
- Outlier handling using **Trimming and Capping**

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 📂 Dataset Columns
- **cgpa** – Student CGPA  
- **placement_exam_marks** – Marks obtained in placement exam  
- **placed** – Placement status (0 = Not Placed, 1 = Placed)

## 📈 Visualizations
- Histogram distribution of CGPA
- Histogram distribution of placement exam marks
- Boxplot for outlier detection
- Distribution comparison before and after outlier removal

## ⚙️ Outlier Detection Method
The project uses the **IQR (Interquartile Range)** technique:

Upper Limit = Q3 + 1.5 × IQR  
Lower Limit = Q1 − 1.5 × IQR  

Outliers are handled using:
- **Trimming**
- **Capping**


## 🚀 Goal
To understand data distribution and improve dataset quality by identifying and handling outliers for better machine learning analysis.