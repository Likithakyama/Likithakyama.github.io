**Work Funnel Analysis**


This Python script analyzes productivity and performance metrics within a manufacturing environment. It utilizes data from an Excel spreadsheet to examine various aspects such as targeted productivity, actual productivity, overtime, and workforce distribution across different departments and quarters.

**Key Features:**

Data Import and Preprocessing: The script starts by importing necessary libraries such as NumPy, pandas, and matplotlib. It loads the dataset from an Excel file and performs initial data exploration, including checking for missing values and filling them with zeros.

|**Target Achievement Classification:**

A new column is added to classify whether the actual productivity meets the targeted productivity. This classification helps in understanding the overall performance.

**Statistical Summaries:**

Descriptive statistics are calculated to summarize key metrics like productivity, overtime, and workforce distribution. This provides insights into the central tendency and variability of the data.

**Visualization:**

The script utilizes Matplotlib and Seaborn to create informative visualizations. It includes bar plots to visualize target achievement by quarter and department, providing a clear overview of performance trends.

**Time Series Analysis:**

An ARIMA model is implemented to analyze the time series of actual productivity. The model helps in understanding patterns and making predictions. Additionally, diagnostic plots are generated to assess the model's residuals.

**Machine Learning Model:**

A linear regression model is trained to predict actual productivity based on targeted productivity, workforce size, and overtime. Evaluation metrics such as mean squared error and mean absolute percentage error are computed to assess model performance.
