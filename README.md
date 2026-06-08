# INFS2822 --- Harbour Brew Market Iced Coffee Sales Analytics

Analysed **17,600+ iced-coffee sales records** for Harbour Brew Market using **Python** within Jupyter Notebook, leveraging libraries including **Pandas, NumPy, Matplotlib, and Seaborn** for data manipulation, statistical analysis, and visualisation. The project aimed to understand key drivers influencing sales performance and identify actionable business insights to support operational and marketing decisions.

**Business Problem**
Harbour Brew Market experienced significant fluctuations in iced-coffee demand throughout the year, management needed to understand how factors such as temperature, seasonal changes, public holidays, and promotional spending influenced sales performance.

**Analysis Apporach**

• Conducted **Data cleaning and Preprocessing** to improve data quality and reliability before analysis. 
This involved identifying and handling missing values, removing duplicate records, validating and correcting data types, checking for inconsistent data formats, and ensuring datasets were structured appropriately for analysis. Applied Pandas functions and techniques such as filtering, grouping, aggregation, and transformation to prepare datasets for further exploration.

• Performed **Exploratory Data Analysis (EDA)** to investigate relationships between sales performance and several business variables including temperature conditions, seasonal trends, public holidays, and promotional spending levels. 
  • **Scatter plots** to examine relationships between temperature, promotional spending, and sales
  • **Heatmaps** for seasonal sales performance across Sydney suburbs
  • **Line charts** to identify seasonal and monthly demand trends
  • **Bar charts** to compare sales performance across holiday and non-holiday periods
  • **Histograms** to analyse sales distributions
  • **Box plots** to identify variability and outliers in sales performanc

**Key Insights**

• **Holiday weeks consistently outperformed non-holiday weeks**, although further analysis revealed that most holiday periods occurred during summer, suggesting temperature may be the true driver of demand.  

• Heatmap analysis showed **summer generated the highest average weekly sales** (≈350–380 units) while spring recorded the lowest (≈220–240 units), demonstrating strong seasonality in customer demand.  

• Temperature proved to be the strongest demand driver, with warmer seasons consistently producing higher sales across all Sydney suburbs.  

• **Promotional spending showed almost no meaningful relationship with sales performance**. Scatter plot analysis revealed a near-horizontal trend line, indicating that increasing promotional budgets did not significantly increase weekly sales.  

• Increasing promotional spending from approximately **$1,500 to $8,000 per week** increased winter sales by **only 30 units**, generating **less than $145 in additional revenue** despite several thousand dollars in additional marketing expenditure.    

• The analysis identified a major business inefficiency: current promotional activities **failed to recover even 5% of their cost**, making promotional spending the weakest sales driver in the dataset.  

**Business Recommendations**
• Increase inventory and staffing ahead of **summer and major holiday periods**.
• Shift operational planning toward weather and seasonal forecasting rather than promotional campaigns.
• **Pause or significantly reduce iced-coffee promotional spending** and conduct a full review of marketing budget allocation.
• Redirect marketing resources toward more effective demand-generation activities and seasonal product strategies.


