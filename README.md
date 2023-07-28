# Sales_Stores
### Overview of the dataset:
+ The dataset contains information on store sales, including various attributes such as id_number, date, retailer, region, state, product, sales_method, price_per_unit, and units_sold. The dataset consists of 9639 entries and has 9 columns.
+ The dataset contains information for the years 2021 and 2022 and it is a monthly data.


### Methods and Questions Explored
+ Pairplot for Data Overview
+ Method: sns.pairplot
+ Question: How do different variables relate to each other in the dataset?

### Distribution of Retailers
+ Method: sns.barplot
+ Question: What is the distribution of sales among different retailers?

### Distribution of Regions
+ Method: sns.barplot
+ Question: How are sales distributed across different regions?

### Distribution of Products
+ Method: sns.barplot
+ Question: What is the distribution of sales for different products?

### Distribution of Sales Methods
+ Method: sns.barplot
+ Question: What are the different sales methods employed, and how do they compare in terms of sales distribution?

### Distribution of States
+ Method: sns.barplot
+ Question: How are sales distributed across different states?

### Total Sales by Month
+ Method: Grouping and sns.barplot
+ Question: What are the total sales for each month, and how do they vary?

### Total Sales by Year
+ Method: Grouping and sns.barplot
+ Question: What are the total sales for each year, and how do they compare?

### Total Sales by Week
+ Method: Grouping and sns.barplot
+ Question: How do the total sales vary on a weekly basis?

### Total Sales Over Time
+ Method: sns.lineplot
+ Question: How have the total sales evolved over time?

### Average Monthly Sales: Yearly Comparison
+ Method: sns.barplot with 'year' as hue
+ Question: How do the average monthly sales compare for different years?

### Total Sales by Product
+ Method: Grouping and sns.barplot
+ Question: What are the total sales for each product, and which products perform best?

### Average Sales by Product: Yearly Comparison
+ Method: sns.barplot with 'year' as hue
+ Question: How do the average sales compare for different products over the years?

### Total Sales by State
+ Method: Grouping and sns.barplot
+ Question: What are the total sales for each state, and how do they differ?

### Distribution of Total Sales by Region
+ Method: plt.pie
+ Question: How are total sales distributed across different regions?

### Average Monthly Sales by Product: Yearly Comparison
+ Method: sns.barplot with 'year' as hue
+ Question: How do the average monthly sales for different products compare over the years?

### Distribution of Total Sales by Sales Method
+ Method: plt.pie
+ Question: What is the distribution of total sales based on different sales methods?

### Distribution of Total Sales by Retailer
+ Method: plt.pie
+ Question: How are total sales distributed among different retailers?

### Average Monthly Sales by Retailer: Yearly Comparison
+ Method: sns.barplot with 'year' as hue
+ Question: How do the average monthly sales for different retailers compare over the years?

### Correlation Matrix and Correlation Plot
+ Method: sns.heatmap
+ Question: What is the correlation between sales, price per unit, and units sold?
