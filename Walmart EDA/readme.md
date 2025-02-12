### Walmart Sales EDA
### ⭐Overview
📌 This project revolves around the exploratory data analysis (EDA) of sales made by Walmart in 45 stores. The objective is to analyze the weekly sales, assess the trends and patterns along with the seasonality and all associated factors.

### 📂 Dataset Information
📄 File: Walmart Dataset.csv
As of now, the dataset maintains 6,435 records with 8 features:
- 🏬 Store: Store number.
- 📅 Date: Sales date.
- 💰 Weekly_Sales: Weekly sales revenue.
- 🎉 Holiday_Flag: Stores holiday flag and accounts for its effects (1 = Yes, 0 =No).
- 🌡 Temperature: Weekly average temperature.
- ⛽ Fuel_Price: Average fuel price for the week.
- 📈 CPI: Consumer Price Index.
- 📉 Unemployment: Unemployment rate.

### 📊 Analysis
📌 This Jupyter Notebook file (Walmart_Sales EDA.ipynb) does the following analysis:
* ✅ Data Cleaning & Preprocessing: Check for insufficient data, repeat data, and ensure correct formatting with split feature
* ✅ Statistical Summary: Identification of critical features mean, median, key and its distribution concentration regions.
* ✅ Time Series Analysis: Analyze the changes for all stores in the weekly sales figures over time.
* ✅ Seasonality Patterns: Identifying the changes in sales over multiple time periods and for different seasons and other such attributes.
* ✅ Holiday Sales Impact: Assessing the extent to which holidays contribute to the powerful surge in sales figures.
* We do correlation analyses to look at how sales are affected by turbo fuel prices, unemployment figures and the consumer price index.
* We do “Store wise comparisons” to analyse well performing powerhouse and draggard stores.
* Insights from the data are provided in dash board form which gives graphs and pie charts.

### Key Findings
#### Top-Performing Stores And Their Performances
- Store 20 is the clear cut leader and has the highest sales of all stores combined.
- Other powerhouse stores are Store 4, 14, 13 and 2.
#### Sales Trends
- There is a lot of variation of sales for all the stores.
- Seasonal trends can be observed, there is a spike during holiday weeks.
#### Impact of External Factors
- Higher unemployment rates tend to have low sales.
- Decision concerning fuel price changes can put more sales out, but in depth study is needed.
#### Data Overview
- The information captured is clean with no missing values.
- Sales per store per week reside in the low hundred thousands and soar into the high single digit millions.
