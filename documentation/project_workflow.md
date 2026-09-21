\# 🔄 Project Workflow



\## 1. Raw Data



The project starts with the raw customer shopping behavior dataset in CSV format.



\*\*Input:\*\*



\* `customer\_shopping\_behavior.csv`



The dataset contains customer, purchase, product, shipping, discount, subscription, and review-related information.



\---



\## 2. Data Cleaning \& Exploratory Data Analysis



Python and Pandas are used to inspect, clean, and prepare the dataset.



\### Activities



\* Data inspection

\* Missing value analysis

\* Data type validation

\* Data cleaning

\* Column standardization

\* Feature engineering

\* Customer segmentation

\* Exploratory data analysis



\*\*Tools:\*\*



\* Python

\* Pandas

\* Jupyter Notebook



\*\*Notebook:\*\*

`Customer\_Shopping\_Behavior\_Analysis.ipynb`



\---



\## 3. Load Data into MySQL



After data preparation, the cleaned dataset is loaded directly into a MySQL database.



\### Database



\* Database System: MySQL

\* Database: `customer\_behavior`



Python uses SQLAlchemy and PyMySQL to establish the database connection and load the prepared data.



\---



\## 4. SQL Business Analysis



MySQL is used to perform business analysis on the prepared customer behavior data.



\### Analysis Areas



\* Customer segmentation

\* Product performance

\* Category analysis

\* Customer spending

\* Discount usage

\* Shipping preferences

\* Subscription behavior

\* Purchase frequency

\* Product ranking

\* Customer purchasing patterns



\*\*SQL File:\*\*



`customer\_behavior\_sql\_queries.sql`



\---



\## 5. Power BI Dashboard



Power BI is used to create an interactive dashboard based on the analytical results.



\### Dashboard Analysis



\* Customer KPIs

\* Average spending

\* Average review ratings

\* Category performance

\* Revenue by age group

\* Subscription behavior

\* Shipping preferences

\* Customer purchasing patterns



\*\*Tool:\*\* Power BI



\---



\## 6. Business Insights



The final stage converts the analytical results into business insights that help understand customer purchasing behavior and identify important trends.



\---



\## 🔁 Complete Workflow



```text

Raw Customer Shopping CSV

&#x20;         ↓

Python / Pandas

&#x20;         ↓

Data Cleaning \& EDA

&#x20;         ↓

MySQL Database

&#x20;         ↓

SQL Business Analysis

&#x20;         ↓

Power BI

&#x20;         ↓

Interactive Dashboard

&#x20;         ↓

Business Insights

```



