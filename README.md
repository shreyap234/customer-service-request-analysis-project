# 📞 Customer Service Request Analysis

## 📌 Project Overview
The **Customer Service Request Analysis** project focuses on analyzing public service complaint data to identify complaint patterns, city-wise issue distribution, and response time performance.

The project includes data cleaning, exploratory data analysis (EDA), visualization, and statistical testing to understand how different complaint types behave across cities and how quickly they are resolved.



## 🎯 Objective
The main objective of this project is to:
- Clean and preprocess service request data
- Identify the most common complaint types
- Analyze complaint distribution across cities
- Measure response time for complaints
- Compare complaint handling efficiency
- Perform hypothesis testing using statistical methods



## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **SciPy**
- **Jupyter Notebook**


## 📂 Dataset Information
The dataset contains customer/public service complaints with fields such as:
- Complaint Type
- Created Date
- Closed Date
- City
- Agency
- Location
- Status-related fields



## 🔧 Data Cleaning Steps
The following preprocessing steps were performed:
- Checked dataset shape (rows and columns)
- Identified missing/null values
- Removed records where **Closed Date** was missing
- Converted **Created Date** and **Closed Date** into datetime format
- Removed records where **Closed Date** was earlier than **Created Date**
- Filled missing values in the **City** column with `"Unknown City"`



## 📊 Analysis Performed
- Total number of complaints for each complaint type
- Number of complaints in each city
- Complaint type distribution across cities
- Complaint type visualizations using bar charts
- Complaint distribution across cities
- Stacked bar chart of complaint types by city
- Average response time for each complaint type
- Comparison of response time across complaint types



## 📈 Statistical Testing
A **Kruskal-Wallis Test** was performed to check whether the response time differs significantly across complaint types.

### Hypothesis:
- **Null Hypothesis (H₀):** Response time is the same across all complaint types
- **Alternative Hypothesis (H₁):** Response time differs across complaint types
-  This test helps determine whether complaint type has a statistically significant impact on service response time.



## 📌 Key Insights
- Certain complaint types occur more frequently than others
- Complaint distribution varies across different cities
- Some complaint categories take longer to resolve
- Statistical testing helps validate whether response time differences are meaningful

