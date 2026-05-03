# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: CHARISHMA BOYINA

*INTERN ID*: CTIS9257

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

## DESCRIPTION:

# Big Data Analysis Using Dask on Online Retail Dataset

## Project Overview

This project presents a comprehensive Big Data analysis performed on a large-scale online retail dataset using the Dask library in Python. The primary objective of this work is to demonstrate the capability of scalable data processing tools in handling large datasets efficiently while extracting meaningful business insights. The dataset consists of transactional records containing information such as invoice details, product descriptions, quantities, pricing, customer identifiers, and geographical data.

The analysis follows a structured data science workflow, including data ingestion, preprocessing, feature engineering, exploratory data analysis (EDA), and visualization. The use of Dask enables parallel computation and efficient memory management, making it suitable for handling datasets that exceed the limitations of traditional in-memory processing tools like Pandas.

---

## Objectives

The key objectives of this project are as follows:

- To perform scalable data processing using Dask
- To clean and preprocess large transactional datasets
- To derive meaningful insights related to sales, customers, and products
- To visualize patterns and trends using statistical and graphical techniques
- To demonstrate the application of big data tools in real-world business scenarios

---

## Tools and Technologies Used

- **Programming Language:** Python  
- **Libraries:**
  - Dask (for scalable data processing)
  - Pandas (for initial validation and compatibility)
  - Matplotlib (for basic visualizations)
  - Seaborn (for advanced statistical visualizations)
- **Platform:** Jupyter Notebook  
- **Dataset:** Online Retail Dataset (CSV format)

---

## Methodology

### 1. Data Loading and Processing
The dataset was loaded using Dask’s `read_csv` function with appropriate configurations to handle encoding issues and mixed data types. Chunk-based processing was utilized to ensure scalability.

### 2. Data Cleaning
The dataset contained missing values and inconsistent data types. Rows with missing critical fields were removed, and relevant columns such as Quantity and UnitPrice were converted into numerical formats. This step ensured the reliability of subsequent analysis.

### 3. Feature Engineering
A new feature, **TotalSales**, was created by multiplying quantity and unit price. This allowed for direct analysis of revenue at the transaction level.

### 4. Exploratory Data Analysis (EDA)
Multiple analytical operations were performed using Dask’s groupby and aggregation functions, including:
- Country-wise revenue analysis
- Product demand evaluation
- Customer contribution analysis
- Time-based sales trend analysis

### 5. Data Visualization
Visualizations were generated using Matplotlib and Seaborn to enhance interpretability. These included bar charts, line plots, histograms, scatter plots, and correlation heatmaps.

---

## Key Insights

- Revenue generation is concentrated in specific countries, indicating regional dependency.
- A limited number of products account for a large portion of total sales.
- Customer spending patterns reveal that a small segment of customers contributes significantly to overall revenue.
- Sales trends exhibit temporal variation, indicating potential seasonality in demand.
- Data distribution analysis highlights skewness and the presence of outliers in transaction quantities.

---

## Applications

This project demonstrates practical applications in several domains, including:

- **Retail Analytics:** Understanding customer behavior, product performance, and sales trends  
- **Business Intelligence:** Supporting data-driven decision-making and strategic planning  
- **Supply Chain Optimization:** Forecasting demand and managing inventory efficiently  
- **Customer Relationship Management (CRM):** Identifying high-value customers for targeted engagement  
- **Big Data Engineering:** Implementing scalable data processing pipelines using distributed computing tools  

---

## Conclusion

This project effectively illustrates how Dask can be leveraged for scalable big data analysis in a real-world retail scenario. By combining efficient data processing techniques with structured analytical methods, the project delivers actionable insights that can support business growth and optimization. The approach demonstrated in this work can be extended to larger datasets and integrated into production-level data pipelines for advanced analytics and machine learning applications.

## OUTPUT:

<img width="1346" height="708" alt="Image" src="https://github.com/user-attachments/assets/0bfa1bc9-4a15-4af3-9c03-d6bbc043a0ca" />

<img width="1394" height="626" alt="Image" src="https://github.com/user-attachments/assets/1ec05d76-3071-4dac-b7da-dda0b7bd88ef" />

<img width="683" height="502" alt="Image" src="https://github.com/user-attachments/assets/b45dfeea-acbb-4ad5-9126-ad86d9ff41d1" />
