# kcluster_analysis
Pharmaceutical Industry Data Analysis
This project involves analyzing a small dataset of financial information from 21 firms in the pharmaceutical industry. The primary goal is to perform clustering analysis to uncover patterns and group similar firms based on their financial characteristics.
________________________________________
Dataset Overview
The dataset contains 21 rows and 14 columns, recording the following variables for each firm:
1.	Market Capitalization (in billions of dollars):
A measure of a company's total value in the stock market.
2.	Beta:
Represents the relationship between systematic risk and expected return. High-beta stocks are riskier with higher return potential, while low-beta stocks pose less risk but also lower returns.
3.	Price/Earnings Ratio:
The ratio of a company's share price to its earnings per share. A high P/E ratio may indicate an overvalued stock or expected high growth rates.
4.	Return on Equity (ROE):
A measure of financial performance, calculated by dividing net income by shareholders' equity.
5.	Return on Assets (ROA):
Indicates how profitable a company is relative to its total assets.
6.	Asset Turnover:
The ratio of total sales or revenue to average assets.
7.	Leverage:
The use of borrowed funds to amplify investment returns.
8.	Estimated Revenue Growth:
The projected increase or decrease in a company’s sales.
9.	Net Profit Margin:
The ratio of net profits to revenues, reflecting overall profitability.
10.	Median Recommendation (across major brokerages):
Analysts' recommendation for buying or holding a firm's stock.
11.	Location of Firm’s Headquarters:
The country where the firm is based.
12.	Stock Exchange:
The stock exchange(s) where the firm’s shares are listed for trading.
________________________________________
Steps Followed in the Analysis
1.	Read the Dataset:
The pharmaceutical dataset was loaded into Python using libraries like pandas for efficient data handling.
2.	Data Exploration and Standardization:
o	Conducted Exploratory Data Analysis (EDA) to understand the dataset structure
o	Standardized the data to ensure all features have a consistent scale for clustering.
3.	Determine the Optimal Number of Clusters (K):
o	Used the Elbow Method, an effective approach to identify the optimal number of clusters.
o	Plotted the within-cluster sum of squares (WCSS) against the number of clusters to visualize the "elbow point."
4.	K-Means Clustering:
o	Applied the K-Means clustering algorithm to group firms based on their financial characteristics.
5.	Visualization and Interpretation of clusters:
________________________________________
Key Skills Demonstrated
I. Data Ingestion and Preparation
II. Data Exploration and Standardization
III. Using the Elbow Method to Determine Optimal K
IV. Performing K-Means Clustering
V. Visualization and Interpretation of Clusters
VI. General Data Analysis and Problem-Solving
________________________________________
Project Outcomes
•	Cluster Insights: Segmentation of pharmaceutical firms based on financial performance and market metrics.
•	Actionable Insights: Identification of patterns that could inform investment decisions or competitive analysis.
________________________________________
Technologies Used
•	Programming Language: Python
•	Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
