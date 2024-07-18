# Econmomic_Fred_EDA

### Introduction to FRED Data:
FRED (Federal Reserve Economic Data) is a comprehensive and widely used database maintained by the Federal Reserve Bank of St. Louis. It provides access to a vast collection of economic data series, covering a wide range of topics such as:

- Macroeconomic Indicators: Data on GDP, inflation, unemployment rates, etc.
- Financial Indicators: Information on interest rates, bond yields, stock market indices, etc.
- International Data: Economic statistics from various countries and regions.
- Labor Market Data: Employment statistics, labor force participation rates, etc.
- Consumer Data: Consumer price indices, personal consumption expenditures, etc.

FRED offers tools for data visualization, charting, and downloading data in various formats, making it a valuable resource for economists, researchers, students, and policymakers. Users can create customized graphs, analyze trends, and incorporate data into their research and reports.

### FRED API
The FRED API also allows developers to access and retrieve data programmatically, which can be integrated into applications and automated processes.
The API's flexibility supports integration into various applications, facilitating automated data analysis and visualization. This empowers researchers, analysts, and developers to effortlessly harness high-quality, up-to-date economic data, significantly enhancing the efficiency and accuracy of their work.

### What's in the project?

The analysis of labor market data, specifically employment statistics and labor force participation rates, is done in this project. Using the FRED API in Python, I efficiently extract, clean, and visualize this data.

-- Step 1: Setup and Data Extraction
Start by installing the necessary libraries: fredapi, pandas, matplotlib, and seaborn. Obtain your FRED API key from the FRED website and initialize the API. Retrieve the required data series.

--Step 2: Data Cleaning
Convert the data into a Pandas DataFrame and handle any missing values by forward-filling them to ensure a continuous dataset. Select the specific and relevent data for futher analysis

--Step 3: Data Visualization
Use Matplotlib, Plotly and Seaborn to create clear visualizations of the data. Plot the employment data and labor force participation rate separately to analyze trends over time. Going further by taking state wise data and analyzing both the rates for each state and compare them.

