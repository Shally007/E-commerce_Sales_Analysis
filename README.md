# E-commerce_Sales_Analysis

### Project overview
This Data Analysis Project aims to provide insight into the sales peformance of a Fintech based in Lagos, in the 2nd and 3rd quarters of the year 2021.By analysing various aspect of the sales data, we seek to identify trends, make data-driven reccomendations and gain a deeper understanding of the companies performance.

### Data Source
The dataset used for this analysis is the "Service Provider New Version.xlsx" file
[Download here](https://github.com/user-attachments/files/17993060/Ari.Logical.Functions.xlsx)

### Tools
- Excel - Data cleaning
  -  [Download here](https://microsoft.com)
- MySQL- Data Analysis
- PowerBI- Data Visualization

###  Data Cleaning
In the preparation of the dataset for analysis, we performed the following tasks:
1. Removal of duplicates
2. Handled missing values with XLOOKUP
3. Changed values to the appropriate format

### Exploratory Data Analysis
The data was explored to answer key questions such as;
- What was the monthly sales trend?
- What were the top performing categories?
- What were the peak sales periods?

### Data Analysis

```MySQL
SELECT payment_date, amount FROM service_provider_table
WHERE category = 'betting'
```

### Dashboard
![Screenshot (3)](https://github.com/user-attachments/assets/6075d198-d2e7-4b37-ace9-9e3aef3b8332)

### Results/Findngs

### Reccomendations
