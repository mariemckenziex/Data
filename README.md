## Hi! Let's wrangle some data and see what adventures await.

I'm a driven professional, fueled by a passion for uncovering insights and facing the ever-evolving challenges of the digital landscape. My career has been a thrilling adventure, navigating diverse roles from Business Development to Web and Digital Project Management. This journey has honed my ability to not only lead successful projects and drive online growth but also to extract meaningful narratives from complex datasets, transforming raw numbers into actionable strategies. I thrive on the intellectual challenge of deciphering user behavior and market trends, much like an explorer charting unknown territories.

## Skills
- Data-Informed Project Management, Strategic Data Visualization & Interpretation, Client-Centric Data Communication, A/B Testing and Optimization, Forecasting and Predictive Analytics, MySQL, PowerBi

## Data Visualization Tools
  - Tableau, PowerBI, Matplotlib, Seaborn, Jupyter
    
Explore my resume [here](https://github.com/mariemckenziex/Data/blob/main/Marie%20McKenzie%20-%20DataCV.pdf)

This repository will showcase my Data Analytics skills, combining those listed above with data cleaning, manipulation, analysis, and visualizations as well as complex high-dimensional transformations.

## Table of Contents

### A. Data Analytics:
#### Programming Languages
  - Python
    - [Credit Card Customer Data Analysis](#credit-card-customer-data-analysis)
  - R
    - [Walmart Stocks](#walmart-stocks-data-analysis)
  - SQL
    - [Ecommerce][coming soon]
  
### B. What's to Come (coming soon)
  - Big Data Processing
  - Apache Spark 
  - Apache Hadoop 

#### Cloud-Based Data Warehousing
  - Google Big Query 
  - Amazon Redshift
  - Microsoft Azure Synapse Analytics

#### Machine Learning and Deep Learning
  - Scikit-learn
  - TensorFlow
  - PyTorch

## Projects
#### Credit Card Customer Data Analysis
##### Code:
[Credit Card Customer Data Analysis](https://github.com/mariemckenziex/Data/blob/main/CreditCardDatAnalysis.ipynb)

##### Project Goals:
The primary goals of this project are to thoroughly understand customer spending behavior by identifying key patterns and relationships within the dataset, improve data quality through comprehensive cleaning and preprocessing to ensure accurate analysis, determine the significant factors influencing spending amounts across various categories such as card type, expense type, and time, create insightful visualizations that effectively communicate spending trends, and ultimately deliver actionable insights that can inform strategic business decisions related to customer spending.

##### Skills:
A. Data Cleaning and Preprocessing:
- Handling missing values (imputation, deletion)
- Duplicate removal
- Data type conversion
- Text standardization
- Outlier detection and removal (IQR)
  
B. Exploratory Data Analysis (EDA):
- Calculating summary statistics (mean, median, standard deviation)
- Data aggregation and grouping
- Data ordering

C. Data Visualization:
- Creating histograms, time series plots, and bar charts using libraries like Seaborn and Matplotlib
- Interpreting and communicating insights from visualizations

D. Statistical Analysis:
- Basic understanding of mean, median, standard deviation, and data distributions

E. Programming:
- Proficiency in Python and pandas for data manipulation

##### Technologies:
Python, Pandas, Numpy, Seaborn, Matplotlib, SciPy.

##### Findings:
1. Overall spending patterns indicate a concentration of spending frequency within the 831-941 range. This suggests a common spending level or bracket among the observed transactions. A spending figure of $350,000 is the least recurring, implying a very high-value but rare transaction.

2. Spending changes over time presents a volatile spending pattern over approximately a year and a half, from November 2013 to May 2015, with spending amounts fluctuating significantly between roughly $100,000 and $250,000. While a central tendency appears around the $150,000 to $175,000 range, the data exhibits frequent peaks and troughs, suggesting an unstable spending behavior rather than a consistent upward or downward trend.

3. Spending based on card type exhibits a close range, with Platinum cardholders demonstrating the highest average spend at $157,493.83, followed closely by Signature at $157,133.72, then Silver at $156,371.03, and Gold with the lowest average spend at $154,631.62. Spending behavior doesn't significantly vary among these card types.

4. Spending across different expense categories illustrates the average distribution across six distinct expense types: Bills, Entertainment, Food, Fuel, Grocery, and Travel. Notably, the "Bills" category exhibits the highest mean spending. Travel" displays the lowest indicating potential areas for budget analysis and financial planning
The remaining categories, Entertainment, Food, Fuel, and Grocery, show intermediate spending levels, falling between these two extremes

#### Walmart Stocks Data Analysis
##### Code:
[Walmart Stocks Data Analysis](https://github.com/mariemckenziex/Data/blob/main/WalmartSP.ipynb)

##### Project Goals:
The primary goal of this project is to conduct an initial exploration and cleaning of the Walmart stock price dataset, importing the data into R, previewing its structure, examining column data types, and addressing data quality issues, missing values, duplicates, and leading/trailing spaces. The project aims to perform an analysis of trading by calculating total volume and visualizing the yearly trend of average daily volume, as well as identifying the daily highest opening and lowest closing prices.

##### Skills:
A. Data Cleaning and Preprocessing:
- Handling missing values 
- Duplicate removal
- Data type conversion
- Leading and Trailing Spaces

B. Exploratory Data Analysis (EDA):
- Summary Statistics
- Data Structure Examination


C. Data Visualization:
- Data Visualization of Volume

D. Statistical Analysis:
- Total Volume Calculation
- Yearly Average Daily Volume
- Basic Analysis of Price Extremes
- one-sample t-test
- Correlation test
- ANOVA
- Linear regression

E. Programming:
- Proficiency in R and pandas for data manipulation


##### Findings:
The assessment performed correlation analysis between opening and closing prices, a hypothesis test on the average daily price change, modeled the long-term price trend using linear regression, visualized price volatility using the standard deviation of returns, calculated and visualized the On-Balance Volume, calculated and visualized Bollinger Bands, and analyzed the percentage change in stock price on a monthly basis.

1. The analysis reveals an extremely tight and statistically significant relationship between Walmart's opening stock price and its closing price on any given trading day. This near-perfect positive correlation suggests that the opening price is an exceptionally strong indicator of where the stock price will end the trading day. Essentially, if the stock opens higher, it is almost certain to close higher, and vice versa, with very little deviation. This indicates high predictability of the closing price based on the opening price within the same trading session.

2. Walmart's average daily price change (the difference between the closing and opening price) shows that while there's a slight positive average change of approximately $0.0035, this daily movement is not statistically significant at the conventional 5% level. Because the 95% confidence interval for this average change includes zero, we cannot confidently say that the price consistently tends to either increase or decrease from its opening value by the end of the day. This suggests that, on average, the daily price fluctuation around the opening price is relatively small and doesn't exhibit a strong directional bias.

3. On-Balance Volume (OBV) Calculation and Visualization: The increasing OBV trend suggests sustained buying interest, potentially preceding or confirming price increases

4. Bollinger Bands Calculation and Visualization: The data shows the stock price of a single entity (given the consistent 'Stock Splits' of 0.0 and 'Dividends' of 0.0 within this timeframe) fluctuating within a relatively narrow range during January 2025. The 'Open', 'High', 'Low', and 'Close' prices are all clustered between approximately 90 and 94, suggesting a period of moderate price stability within this short window. The 'Volume' column indicates varying levels of trading activity day-to-day, ranging from 1.33e+07 to 2.32e+07 shares traded. This suggests consistent market interest in the stock, but without a longer historical context, it's difficult to determine if these volume levels are high, low, or typical.

5. Relative Strength Index (RSI) and Moving Averages: The data shows a discernible upward trend in the stock price. Starting in late January around the mid-90s, the closing price generally climbs, reaching the low 100s by early February and then continuing to fluctuate mostly in the 102-105 range in mid-February. There's a noticeable dip around February 20th before a partial recovery. The trading volume remains variable, ranging from approximately 1.1e+07 to 3.5e+07 shares. The highest volume observed in this snippet occurs around the price dip in late February, which could indicate increased selling pressure or market reaction to an event not visible in this data alone.

6. Monthly Percentage Change: The initial monthly performance shows significant volatility and a lack of sustained positive growth. Several months have experienced substantial losses, highlighting a potentially turbulent early phase for the company's publicly traded shares. The early months (August to December 1972) show significant fluctuations in Walmart's stock price. Both substantial losses (e.g., -3.03% in August, -9.69% in September, -4.45% in November) and notable gains (e.g., +5.74% in October, +5.34% in December). This suggests a period of high initial volatility for the stock. This pattern of significant monthly swings continues into 1973. January 1973 experienced a sharp decline of -14.4%, followed by smaller gains in February (+2.48%) and a very substantial loss in March (-26.0%). The subsequent months of April and May 1973 show smaller percentage decreases (-2.19% and -1.13%, respectively), indicating a potential slowing down of the sharp downward trend seen in March.


