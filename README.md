📈 FINANCIAL DATA ANALYSIS USING PYTHON: A CASE STUDY OF HDFC BANK STOCK PRICES

📌 Project Overview
This project explores historical HDFC Bank stock prices from February 2018 to February 2020 using Python. The analysis includes data cleaning, price visualization, daily return calculation, and daily change categorization.

🎯 Objectives
- Prepare and clean stock trading data.
- Visualize historical stock price movements.
- Analyze daily returns and their distribution.
- Categorize daily changes using predefined rules.
  
📊 Dataset
The project uses HDFCBANK.NS.csv, covering February 15, 2018–February 14, 2020.
- Initial dataset: 491 rows and 7 columns.
- After cleaning: 490 rows.
- Valid daily returns: 489 observations.
- Columns: Date, Open, High, Low, Close, Adj Close, and Volume.
- Price currency: Indian Rupee (INR).

🛠 Tools & Technologies
- Google Colab and Python.
- Pandas and NumPy for data processing.
- Matplotlib for visualization.
- gdown for downloading the dataset.

🔄 Project Workflow
1. Load and inspect the dataset.
2. Remove missing values and convert dates.
3. Summarize the last 90 trading observations.
4. Visualize adjusted closing prices.
5. Calculate and analyze daily returns.
6. Categorize daily changes and present findings.

📈 Key Results
- Mean daily return: +0.063%.
- Median daily return: +0.020%.
- Lowest daily return: −3.61%.
- Highest daily return: +8.95%.
- Middle 50% of returns: −0.597% to +0.693%.
- Largest category: Slight or No Change, with 192 observations (39.3%).

💡 Key Insights
- Cleaning removes one incomplete trading record.
- Average daily returns are slightly positive.
- Small daily price changes occur frequently.
- Large increases and decreases occur occasionally.
- Slight or No Change is the most common category.

🚀 Recommendations
- Check missing values and date order before calculating returns.
- Interpret averages alongside the histogram and standard deviation.
- Use quartiles to explain typical daily changes.
- Investigate the dates of unusually large returns.
- Clearly document the thresholds for each category.

🏁 Conclusion
Python helps turn historical stock data into clear statistics and visualizations. This analysis shows that small daily changes are common, alongside occasional large movements. The findings describe historical performance and do not predict future prices.
