 **COVID-19 Data Analysis & Dashboard System** 

 **Project Overview**

The COVID-19 pandemic generated massive amounts of data across the world, including confirmed cases, deaths, recoveries, and active cases. 
Analyzing such data is essential to understand trends, identify patterns, and support decision-making.

However, accessing real-world datasets can sometimes be challenging due to availability, size, or dependency issues. To address this, this 
project introduces a **COVID-19 Data Analysis System using Synthetic Data**.

In this project, a dataset is generated using the Python Faker library to simulate realistic COVID-19 statistics. The generated data is then 
used to perform **Exploratory Data Analysis (EDA)** and visualization to understand trends and relationships.



 **Objective**

The main objective of this project is to analyze COVID-19 trends using a self-generated dataset and derive meaningful insights. The key goals include:

* Generate a realistic synthetic dataset using Faker
* Simulate COVID-19 case patterns across countries
* Perform data cleaning and preprocessing
* Analyze trends over time
* Compare country-wise data
* Identify relationships between variables
* Visualize data using charts and graphs
* Extract insights from the analysis
  

 **Dataset Description**

The dataset is synthetically generated and contains multiple records representing COVID-19 statistics across different countries and dates.

| Column Name | Description               |
| ----------- | ------------------------- |
| Date        | Observation date          |
| Country     | Country name              |
| Confirmed   | Total confirmed cases     |
| Deaths      | Total deaths              |
| Recovered   | Total recovered cases     |
| Active      | Active cases (calculated) |



 **Technologies Used**

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Faker


**Project Workflow**

 **1. Data Generation**

* Dataset is created using the Faker library
* Random values simulate real-world COVID patterns
* Multiple countries and dates are included

 **2. Data Cleaning & Preprocessing**

* Converted date column to proper datetime format
* Removed duplicate records
* Handled missing values
* Ensured numerical consistency

 **3. Exploratory Data Analysis (EDA)**

* Calculated total confirmed, deaths, and recoveries
* Analyzed data distribution
* Studied trends over time

 **4. Trend Analysis**
 
* Observed growth of confirmed cases over time
* Identified peak periods
* Compared daily changes

 **5. Country-Based Analysis**

* Identified most affected countries
* Compared confirmed, deaths, and recoveries
* Analyzed country-wise distribution

 **6. Relationship Analysis**

* Confirmed vs Deaths
* Confirmed vs Recovered
* Active vs Confirmed
* Correlation between variables

 **7. Data Visualization**

* Line chart → Trend over time
* Bar chart → Country comparison
* Pie chart → Case distribution
* Scatter plot → Relationships
* Heatmap → Correlation analysis
* Interactive charts using Plotly


**Key Insights**

* COVID-19 cases show fluctuating trends over time
* Some countries consistently report higher cases
* Strong relationship exists between confirmed and deaths
* Recovery rates vary across countries
* Active cases depend heavily on recovery trends


**How to Run the Project**

**Step 1: Install Required Libraries**

pip install pandas numpy matplotlib seaborn faker plotly


**Step 2: Run the Project**

* Google Colab
* Jupyter Notebook
* VS Code

 **Step 3: Output**


covid_fake_dataset.csv


 **Project Structur**e

COVID-Data-Analysis/
│
├── covid_analysis.py
├── covid_fake_dataset.csv
├── README.md
└── visualizations/


**Future Improvements**

* Build interactive dashboard using Plotly Dash
* Integrate real-time COVID dataset
* Apply machine learning models for prediction
* Deploy as a web application


**Output Overview:**

<img width="798" height="599" alt="image" src="https://github.com/user-attachments/assets/64703014-d1f1-4f38-8e82-42c6d1485c55" />

<img width="1259" height="750" alt="image" src="https://github.com/user-attachments/assets/cd3d4286-13e9-4ffe-96c0-dffbcc28ab28" />

<img width="1137" height="846" alt="image" src="https://github.com/user-attachments/assets/eb7a38c1-d2fc-40ba-aac8-c390ecab2ab1" />

<img width="1190" height="749" alt="image" src="https://github.com/user-attachments/assets/11df4d0b-f119-4650-92fc-dcaace7b452a" />

<img width="858" height="661" alt="image" src="https://github.com/user-attachments/assets/abea6941-5a6a-4a5d-8314-065c50ccd1ed" />

<img width="1630" height="659" alt="image" src="https://github.com/user-attachments/assets/36a42b2c-1733-4f87-b6ea-62c85fb043e8" />


 **Conclusion**

This project demonstrates how synthetic data can be effectively used for analysis when real-world datasets are unavailable.
It helps in understanding data trends, visualization techniques, and real-world project workflows.


**Acknowledgement**

This project is created for educational purposes to learn data analysis and visualization techniques.

