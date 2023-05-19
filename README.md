# **Data Portofolio**
## 👋 **Introduction**

Hi! I'm Faiz, an aspiring data analysis or data science professional who seeking to apply my knowledge to real-world experiences. 
Recently graduated from the bootcamp Data Science: Machine Learning Specialization program at Rakamin Academy, in which I got to learn end-to-end data science processes. 

This repository is containing a portfolio of data science and data analyst projects that I have completed and showcases my skills and experience in this field. My portfolio includes projects that demonstrate my ability to gather, process, and analyze large data sets, as well as my expertise in creating meaningful insights and visualizations.
<br>


### **Table of Content**
- [SQL](https://github.com/faizns/Faizs-Data-Portofolio#-sql)
  - [Analyzing eCommerce Business Performance with SQL](https://github.com/faizns/Faizs-Data-Portofolio#-analyzing-ecommerce-business-performance-with-sql)
  - [Analyzing Website Traffic and Performance](https://github.com/faizns/Faizs-Data-Portofolio#-analyzing-website-traffic-and-performance)
- [Python](https://github.com/faizns/Faizs-Data-Portofolio#-python)
  - [Investigate Hotel Business using Data Visualization](https://github.com/faizns/Faizs-Data-Portofolio#-investigate-hotel-business-using-data-visualization)
  - Predict Customer Personality to Boost Marketing Campaign
  - Predict Customer Clicked Ads Classification
  - Improving Employee Retention by Predicting Employee Attrition
  - [Online Shoppers Purchasing Intention](https://github.com/faizns/Faizs-Data-Portofolio#-online-shoppers-purchasing-intention)
  - [Airline Customer Segmentation Based on LRFMC Model Using K-Means](https://github.com/faizns/Faizs-Data-Portofolio#-airline-customer-segmentation-based-on-lrfmc-model-using-k-means)
- [Dashboard](https://github.com/faizns/Faizs-Data-Portofolio#-dashboard)
  - [Indonesia Covid-19 Dashboard](https://github.com/faizns/Faizs-Data-Portofolio#-indonesia-covid---19-dashboard)
  - [Sales Report Dashboard - VIX Big Data Analytics Kimia Farma](https://github.com/faizns/Faizs-Data-Portofolio#-sales-report-dashboard---vix-big-data-analytics-kimia-farma)
  - [Targeted Customer Demographic Dashboard - VIX Data Analytics KPMG Australia](https://github.com/faizns/Faizs-Data-Portofolio#-targeted-customer-demographic-dashboard-vix-data-analytics-kpmg-australia)
<br>


## 📚 **SQL**
---
### 📂 **Analyzing eCommerce Business Performance with SQL**
[**View Full Documentation**](https://github.com/faizns/Analyzing-eCommerce-Business-Performance-with-SQL)

📍 **Description :** <br>
The dataset has  99441 records containing table of customers, sellers, products, and orders. The objectives are measuring the business performance of e-commerce in Brazil based on:
- Annual Customer Activity Growth
- Annual Product Category Quality
- Annual Payment Type Usage

In general, the company's business performance has grown from 2016 to 2018. there was an addition of new customers and monthly active users increasing by 16% in the past year. Product quality also increases with best-selling products are health and beauty categories. The credit card is the most favorite customer payment method all the time.
<br>
<br>

🛠 **Tools :** <br>
Postgresql, PgAdmin, Ms. Excel for Visualization
<br>
<br>

💻 **Function :**<br>
CREATE TABLE, DATEPART, ALTER, CASE WHEN, JOIN, CTE, Aggregate Function, Window Function, create ERD
<br>
<br>

---
### 📂 **Analyzing Website Traffic and Performance**
[**View Full Documentation**](https://github.com/faizns/Udemy-Advanced-MySQL-Data-Analysis/blob/main/MID_COURSE_PROJECT.md)

📍 **Description :** <br>
This project is from [Advanced SQL: MySQL Data Analysis and Business Intelligence](https://www.udemy.com/course/advanced-sql-mysql-for-analytics-business-intelligence/?src=sac&kw=advanced+sql).

Maven Fuzzy Factory has been live for 8 months. The CEO is due to present company performance metrics to the board next week. I was tasked to extract and analyze website traffic and performance data from the database to quantify the company’s growth.

From the analysis, we can conclude :
- E-commerce business performance is growing. The revenue conversion rate steadily increased by 3.19% from March to 4.40% in November.
- Most traffic from gsearch, nonbrand campaigns, and desktop as device type
- The landing page version of lander-1 can increase the conversion rate by 1.08% higher than the home page with an estimated addition of 64 orders per month.
- From the billing test page, the billing-2 has a larger revenue per billing page contribution with a lift of 8.51 dollars per page view. That had a positive impact on increasing revenue by 10152.43 dollars last month.
<br>

🛠 **Tools :** <br>
MySQL, SQL Workbench
<br>
<br>

💻 **Function :**<br>
Aggregate Function, CASE WHEN Function, Window Function, JOIN, CTE, Temporary Table, Subqueries, Pivoting Data with COUNT and CASE, DATE Function
<br>
<br>
<br>


## 📚 **Python**
---
### 📂 **Investigate Hotel Business using Data Visualization**
[**View Full Documentation**](https://github.com/faizns/Investigate-Hotel-Business-using-Data-Visualization)

📍 **Description :** <br>
This analysis, conducted as a mini-project by Rakamin Academy, focuses on evaluating the performance of the hotel industry using visualizations. The objective is to identify issues, weaknesses, and strengths within the hotel business by understanding customer behavior and adjusting strategies accordingly.

In summary, City Hotel dominates in customer bookings, especially during holiday seasons. Cancellation rates tend to increase with longer stays, particularly in City Hotel. Shorter lead times result in fewer cancellations, while City Hotel faces higher cancellation rates for longer lead times. Resort Hotel exhibits a consistent cancellation rate of around 40%.
<br>
<br>

🛠 **Library :**<br>
Pandas, Matplotlib, Seaborn
<br>
<br>

💻 **Area :**<br>
Data Cleaning and Manipulation, EDA, Data Visualization
<br>
<br>

---

### 📂 **Online Shoppers Purchasing Intention**
[**View Full Documentation**](https://github.com/faizns/Online-Shoppers-Purchasing-Intention) | [**View Presentation**](https://github.com/faizns/Online-Shoppers-Purchasing-Intention/blob/main/Majestic%20Final%20Presentation.pdf)

📍 **Description :** <br>
This was completed for Rakamin Academy's final project.

Majestic is an e-commerce company that only generated a 15% conversion rate on the website in a year. In 2020 - 2021, conversion rates in various e-commerce industries have increased by an average of 28%. This is a great opportunity for companies to increase revenue. We built a model that can predict which website visitors are probable to purchase or not. We also analyze visitor activity to gain insights to provide the ideal business recommendations.

Based on several algorithms that have been tested, Random Forest Hyperparameter Tuning has the best performance. The model achieves a ROC-AUC of 0.90 and from simulation can increase the conversion rate by 58%.
<br>
<br>

🛠 **Library :**<br>
Pandas, Matplotlib, Numpy, Seaborn, Sklearn
<br>
<br>

💻 **Area :**<br>
Data Cleaning and Manipulation, EDA, Supervised Learning, Classification
<br>
<br>

---

### 📂 **Airline Customer Segmentation Based on LRFMC Model Using K-Means**
[**View Full Documentation**](https://github.com/faizns/Airline-Customer-Segmentation-Based-on-LRFMC-Model-Using-KMeans)

📍 **Description :** <br>
This project was completed for Rakamin Academy's homework.

Help airline companies to maximize profits by focusing resources and marketing on valuable customers. We built a clustering model to segment and analyze customer characteristics based on LRFMC scores using K-Means and suggest business strategy recommendations.

From the model results, 5 clusters were obtained: 26% are New Users, 20% are Loyal Customers, 19% are Potential Loyalists/The Campion, 18% are Need Attention, and 16% are Hibernating.
<br>
<br>

🛠 **Library :**<br>
Pandas, Matplotlib, Numpy, Seaborn, Sklearn, Yellowbrick,
<br>
<br>

💻 **Area :**<br>
Data Cleaning and Manipulation, EDA, Unsupervised Learning, K-Means, PCA
<br>
<br>
<br>

## 📚 **Dashboard**
---
### 📂 **Indonesia Covid-19 Dashboard**
[**View Dashboard on Looker Data Studio**](https://lookerstudio.google.com/reporting/f318d486-1675-405f-ad48-c58a11a3a842)

📍 **Description :** <br>
This project (team) was done to complete one of the challenges in the FGA program, Data Science Batch 1 - Kominfo x Binar Academy. We created a dashboard that displays information about the update of COVID cases in Indonesia, such as new active cases, new confirmed cases, new deaths, and recoveries.<br>
<br>

🛠 **Tools :** <br>
Looker Data Studio, BigQuery
<br>
<br>

<p align="center">
  <kbd> <img width="800" alt="Covid _Dashboard_-_Kelompok_DS-3-J_page-0001" src="https://user-images.githubusercontent.com/115857221/226123784-3ae8ccc5-af6b-484f-b4a2-ff1356786b18.jpg"> </kbd> <br>
</p>
<br>
<br>

---

### 📂 **Sales Report Dashboard - VIX Big Data Analytics Kimia Farma**
[**View Full Documentation**](https://github.com/faizns/VIX-Big-Data-Analytics-Kimia-Farma) | [**View Dashboard on Looker Data Studio**](https://lookerstudio.google.com/reporting/3c67b292-3be2-484d-bc29-27bd0b4015fd)

📍 **Description :** <br>
In this project, I worked as a Data Analyst Intern who was asked to analyze and create company sales reports based on provided data. 

Task :
- Created a database with the following dataset in sales, customer, and item
- Queried dataset into the base table and aggregate table using MySQL
- Built an interactive dashboard from sales data in a half year using Google Data Studio<br>
<br>

🛠 **Tools :** <br>
Looker Data Studio, MySQL
<br>
<br>

<p align="center">
  <kbd> <img width="800" alt="Kimia_Farma_page-0001" src="https://user-images.githubusercontent.com/115857221/222877035-53371a89-081d-4ec5-9e72-65b0176a96fd.jpg"> </kbd> <br>
</p>
<br>
<br>

---
### 📂 **Targeted Customer Demographic Dashboard - VIX Data Analytics KPMG Australia**
[**View Full Documentation**](https://github.com/faizns/VIX-Data-Analytics-KPMG-AU) | [**View Dashboard on Tableu**](https://public.tableau.com/app/profile/faiz.naida.salimah/viz/TargetedCustomersDemographicDashboard-KPMGVIX/TargetedCustomerDemographic)

📍 **Description :** <br>
KPMG is a global organization of independent professional firms that provides a range of services to organizations across various industries, government, and non-profit sectors. Under the KPMG Digital Solutions service, as part of the Data, Analytics & Modeling team, we will effectively analyze data sets to help Sprocket Central Pty Ltd, a bike and bike accessories company, develop and optimize its marketing strategies.

Task :
- Reviewed the data based on Standard Data Quality Dimensions and identified strategies to mitigate that issues
- Built customer segmentation based on RFM model and analyzed customer trends, behaviour, and demographic
- Developed interactive dashboard <br>
<br>

🛠 **Tools :** <br>
Tableau, Python
<br>
<br>

<p align="center">
  <kbd> <img width="800" alt="msg" src="https://user-images.githubusercontent.com/115857221/217406894-3088170d-d115-42ba-94b5-1a72af175f9b.png"> </kbd> <br>
</p>
<br>
<br>

---

## **Let's collaborate together!**
- [LinkedIn](https://www.linkedin.com/in/faizns/)
- [Tableau](https://public.tableau.com/app/profile/faiz.naida.salimah)
- Email: naidasalimah@gmail.com
