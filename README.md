# 🛒 Integrated Retail Analytics for Store Optimization

This project demonstrates an **end-to-end data science workflow** applied to retail data.  
The goal is to analyze store performance, detect anomalies, segment stores, and build predictive models to support **data-driven retail optimization**.

---

## 📌 Problem Statement
Retail businesses generate massive amounts of transactional and operational data across different stores and departments.  
However, without effective analytics, it becomes difficult to:
- Detect unusual sales behavior (anomalies)  
- Identify similar groups of stores (segmentation)  
- Forecast sales using predictive modeling  
- Support decision-making for promotions, stocking, and resource allocation  

This project aims to solve these challenges through **integrated analytics and machine learning**.

---

## 🎯 Objectives
- Perform **data cleaning, preprocessing, and feature engineering**  
- Conduct **Exploratory Data Analysis (EDA)** for insights into sales patterns  
- Detect **anomalies** in sales trends  
- Segment stores using **clustering techniques**  
- Build and evaluate a **Random Forest regression model** for sales forecasting  
- Visualize results through intuitive plots  

---

## 📂 Project Structure
Retail-Analytics-Store-Optimization/
│── Dataset/ # Raw datasets (sales, features, stores)
│── plots/ # Visualization outputs
│── detected_anomalies.csv # Anomaly detection results
│── store_segments.csv # Store segmentation results
│── feature_cols.json # Feature engineering details
│── Integrated_Retail_Analytics_for_Store_Optimization.ipynb # Main notebook
│── requirements.txt # Python dependencies
│── .gitignore # Ignored files (large/system files)


---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning**: Random Forest Regression, Clustering (KMeans)  
- **Tools**: Jupyter Notebook, Git, GitHub  

---

## 📊 Key Features
- **Data Preprocessing** – handled missing values, transformations, and scaling  
- **EDA & Visualization** – weekly trends, holiday effects, store types, correlations  
- **Anomaly Detection** – identified abnormal sales patterns  
- **Segmentation** – grouped stores based on key performance metrics  
- **Predictive Modeling** – trained and evaluated Random Forest model for sales  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/shibamdutta99/Retail-Analytics-Store-Optimization.git
   cd Retail-Analytics-Store-Optimization
   
2. Install dependencies:
pip install -r requirements.txt

3. Launch Jupyter Notebook:
jupyter notebook Integrated_Retail_Analytics_for_Store_Optimization.ipynb

## 📌 Results & Conclusion

Sales anomalies were successfully detected, helping to highlight unusual store performance.

Store segmentation revealed distinct behavioral groups, enabling targeted strategies.

Random Forest regression achieved promising predictive performance, supporting data-driven decision making.

Visualizations provided actionable insights into weekly trends, holiday impacts, and feature importance.

This integrated pipeline can be extended for real-world retail optimization and business intelligence.

## 🔗 Notes

The trained model (rf_sales_model.joblib, ~3GB) has been excluded due to GitHub file size limits.

Datasets are provided in the Dataset/ folder (light versions). For full data/model access, please contact the author.

📧 Email: shibam.work@gmail.com
💼 LinkedIn: https://www.linkedin.com/in/shibam-dutta-6a644a43/
