
## Portfolio Projects

In this section I list data‐analytics projects, briefly describing the technology stack used to solve each case.

---

### Youtube  and Spotify Dataset

**code** https://github.com/sam-Adk/Data-analysis-project/blob/main/youtube%20and%20spotify%20dataset.ipynb


**Goal**  The goal of this project is to analyze how different engagement metrics—such as likes, comments, views (on YouTube) and popularity scores or follower counts (on Spotify)—influence the number of streams a song or video receives. By comparing YouTube and Spotify data, the analysis aims to uncover patterns in listener/viewer behavior and determine whether social engagement can predict streaming succes

**Description**  

-Positive Correlation Between Views and Streams: Videos with more YouTube views generally correspond to higher Spotify streaming numbers, suggesting that exposure on one platform may influence listening on another.

-Likes Matter More Than Comments: While comments are valuable for engagement, the number of likes showed a stronger relationship with total streams, indicating that positive viewer sentiment may better reflect popularity.

-Outliers Exist: Some tracks had relatively low YouTube engagement but high Spotify streams, likely due to playlist placements or artist popularity. Conversely, some viral videos did not translate to Spotify success.

-Release Timing and Genre: Songs released closer to peak streaming periods (e.g., weekends or holidays) tended to perform better. Certain genres (e.g., pop, hip-hop) showed stronger cross-platform engagement

## 📁 Data Sources

- YouTube data scraped using [YouTube API / third-party tool]
- Spotify track and artist data obtained via Spotify Web API
- Data cleaned and merged using Python (pandas), with visualization using seaborn/matplotlib

## 🔍 Methods

- Correlation analysis between views, likes, comments, and Spotify streams
- Regression models to test predictive power of engagement metrics
- Outlier detection for viral content with unusual patterns











### India Census Data


**code** https://github.com/sam-Adk/Data-analysis-project/blob/main/india%20census.ipynb

**Goal** The goal of this project is to explore demographic trends in India's population using census data. This includes analyzing population growth, age distribution, rural vs urban populations, and state-wise comparisons to identify long-term patterns and regional difference

**Description** 


-Gender Ratio: Several northern states show a gender imbalance, with fewer females per 1,000 males, while some southern states have near-equal or better female-to-male ratios.

-Literacy Rates: Kerala has the highest literacy rate, while Bihar and Arunachal Pradesh have some of the lowest.

-Urbanization: States like Delhi and Maharashtra are highly urbanized, while states like Bihar and Assam remain predominantly rural.

-Workforce Participation: A significant portion of the female population is not part of the formal labor force, especially in rural region












### Googgle Playstore App Data set

**Code** https://github.com/sam-Adk/Data-analysis-project/blob/main/Google%20PlayStore%20App%20DATA%20set%20(1).ipynb

**Goal** the main purpose was to i dentify what influences app downloads and purchases on Google playstore

**Description**

- I found out that Free apps were more downloaded than those that were to be purchased
- 
- some unique had the highest ratings ,eg events and education
- 
- apps that had the maximum Reviews were Facebook and whatsapp
  
### Procurement KPI analysis

**code** https://github.com/sam-Adk/Data-analysis-project/blob/main/Procurement%20KPI%20Analysis%20Dataset.ipynb

**Goal** This workflow—data ingestion, cleaning, KPI computation, and visualization—is a solid foundation for procurement performance analysis

**Desription**

- Data quality (missing values)

- Supplier performance, via metrics like defective units and delivery frequency
- 
- Cost analysis, via unit prices versus negotiated prices

- Category-level pricing trends

- Distributional patterns of prices



### Adult Csv Project

**code**https://github.com/sam-Adk/Data-analysis-project/blob/main/Adult%20Csv%20project.ipynb

**Goal** determine if age gender and eduational level determine the level of income

**Description**
- involves cleaning anlyzing datasets to coming up with a conclusion
- focusing on determining what determines the level of income based on gander ,age and level of education
- found out  more male  had more chance to get more salaries above 50k than females
- also found out that some workclass were paid more than other working class
- also the income increaed with age


### Cleaning and Analyzing a Police Dataset

**Code:** https://github.com/sam-Adk/Data-analysis-project/blob/main/Cleaning%20and%20analysing%20a%20Police%20DataSets.ipynb

**Goal:** Determine which demographic factors (gender, age, race) are most associated with reckless driving.

**Description:**  
- Involved data loading, cleaning, exploratory data analysis (EDA), correlation analysis, and Pearson’s test.  
- Focused on accident occurrences by race, age, and gender.

**Skills:** data cleaning, EDA, correlation matrices, hypothesis testing, data visualization  
**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib  
**Results:**  
- Found that males were stopped for speeding and involved in accidents more often than females.

---

### E-commerce Purchases Analysis

**Code:** https://github.com/sam-Adk/Data-analysis-project/blob/main/E-%20commerce%20purchases%20dataset.ipynb

**Goal:** Identify which factors contribute most to tax revenue from E-commerce sales.

**Description:**  
- Loaded and cleaned transaction data.  
- Performed EDA, correlation analysis, and Pearson’s test.

**Skills:** data cleaning, EDA, correlation matrices, hypothesis testing, data visualization  
**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, SciPy  
**Results:**  
- Discovered that Mastercard users’ purchases increased with monthly income.

---

### London Housing Data Analysis

**Code:**   https://github.com/sam-Adk/Data-analysis-project/blob/main/London%20Housing%20Data%20Set.ipynb

**Goal:** Examine how housing costs in London have changed over time.

**Description:**  
- Loaded and cleaned housing price data from 1995 to present.  
- Analyzed trends in price increases and correlated with crime statistics.


---

### SanFransico Salaries

**code** https://github.com/sam-Adk/Data-analysis-project/blob/main/SF%20salaries.ipynb

**Goal**  Quantify how much of total compensation is base salary vs. benefits vs. overtime across all employees

**Description**
-Calculate descriptive statistics (mean, median, IQR) for salaries, overtime, other_salaries, total_benefits, and total_compensation columns 
-cleaning and analyzing the datasets missing values
















**Skills:** data cleaning, time-series analysis, data visualization  
**Technology:** Python, Pandas, Matplotlib  
**Results:**  
- Observed a steady increase in housing prices since 1995, alongside a rise in reported crime rates.



##📊 Power Bi Projects

In this section I list Power BI–focused analytics projects, briefly describing the business problem, datasets, methods, and insights delivered through interactive dashboards.

## 🛒 Retail Sales Performance Dashboard (Power BI)

**Dashboard**: Power BI Service (Public)
**Code**: https://github.com/sam-Adk/PowerBI-Retail-Sales

**Goal**
The goal of this project is to analyze retail sales performance across regions, product categories, and time periods to identify revenue drivers and underperforming areas.

Description

**Regional Performance**: Certain regions consistently outperformed others, contributing the majority of total revenue.

**Product Category Trends**: Electronics and home appliances generated the highest revenue, while some categories showed high sales volume but low profitability.

**Seasonality Effects**: Sales peaked during holiday periods, with noticeable drops in off-season months.

**Customer Segmentation**: A small percentage of customers accounted for a large share of total sales.

## 📁 Data Sources

Retail sales transaction dataset (public business dataset)

Customer and product dimension tables

Data cleaned and modeled using Power Query

🔍**Methods**

Star schema data modeling

DAX measures for total sales, profit margin, and YoY growth

Drill-through and slicers for region, category, and date

### 🏥Healthcare Appointment & Wait-Time Analysis

**Dashboard**: Power BI Service (Public)
**Code**: https://github.com/sam-Adk/PowerBI-Healthcare-Analytics

**Goal**
Analyze hospital appointment data to understand patient wait times, appointment outcomes, and operational efficiency.

**Description**

Wait-Time Analysis: Certain departments experienced significantly longer average wait times than others.

**Appointment Outcomes**: Missed and canceled appointments were more frequent during peak hours.

**Operational Bottlenecks**: Staffing shortages correlated with increased delays in specific time windows.

**Patient Flow Trends**: Morning hours handled the highest appointment volumes.

## 📁 Data Sources

Public healthcare appointment dataset

Department and scheduling data

Data transformed using Power Query

**🔍 Methods**

Time-based analysis using DAX

KPI calculations for average wait time and no-show rates

Interactive dashboards with department-level drill-downs

💳 Financial Transactions & Fraud Risk Dashboard

**Dashboard**: Power BI Service (Public)
**Code**: https://github.com/sam-Adk/PowerBI-Financial-Transactions

**Goal**
Identify transaction patterns and potential fraud risk indicators using transaction-level financial data.

**Description**

**High-Risk Transactions**: Large transaction amounts and unusual transaction times showed higher fraud likelihood.

**Geographic Patterns**: Certain regions recorded higher concentrations of flagged transactions.

**Customer Behavior**: New customers exhibited higher fraud risk compared to long-term users.

**Transaction Channels**: Online transactions showed higher risk compared to in-person transactions.

## 📁 Data Sources

Public financial transaction dataset

Customer and merchant reference data

Data cleaned and modeled using Power Query

**🔍Methods**

Risk scoring using calculated DAX measures

Trend and anomaly analysis

Dashboard filters for transaction type, region, and risk level
