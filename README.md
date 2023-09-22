# Web Scraping, Data Analysis, and Visualization of Largest Companies by Revenue

## Introduction
This project encompasses the methodologies of web scraping, data analysis, and visualization to explore the largest companies in the United States by revenue, as listed on Wikipedia. It aims to delve into the intricate details of different companies spread across diverse industries, unveil correlations, and deduce meaningful insights related to revenue, profit, and employee strength.

## Technologies Used
- Python
- BeautifulSoup
- Pandas
- Matplotlib
- Seaborn
- Requests
- CSV

## Workflow

### 1. Web Scraping
- Utilized `requests` and `BeautifulSoup` to scrape data from [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue).
- Extracted relevant information like Rank, Name, Industry, Revenue, Revenue Growth, Employees, and Headquarters.
- Stored the scraped data in a CSV file for further analysis.

### 2. Data Loading and Cleaning
Loaded the data from the CSV file using Pandas.
Performed data cleaning to handle missing values and transform data types where necessary.

## 3. Exploratory Data Analysis (EDA) and Visualization
Analyzed various attributes of the companies.
Used Matplotlib and Seaborn for visualizing distributions, correlations, and patterns in the data.

## Conclusions
Correlation Analysis: A negative correlation of -0.77 was observed between Rank and Revenue, indicating that companies with higher revenues have a lower rank (i.e., are ranked higher). The correlation between Revenue and Revenue Growth was -0.096, suggesting no significant linear relationship between them.
Industry Analysis: The Healthcare industry demonstrated the highest box plot value, approximating 30,000, followed by the Petroleum industry and Retail around 18,000 and 15,000 respectively.
Revenue Distribution: The histogram indicated a right-skewed distribution of revenue, with the highest point at (0,30).
Top Companies Analysis: Walmart showed the highest revenue close to 600,000 USD million, followed by Amazon, Exxon Mobil, and Apple with revenues around 500,000, 400,000, and 400,000 USD million respectively.
Usage
This project is open for enhancements and can be used to understand the economic landscape of the largest companies in the United States by revenue. The analysis and visualizations can aid in decision-making processes related to investments, market analysis, and economic research.

**Notes**
Ensure that you have all the necessary libraries installed and have set up your Python environment properly to run the project successfully.

