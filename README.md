# Superstore Data Analysis Using AWS Services

### Project Architecture 

![proj diag](https://github.com/user-attachments/assets/adfbd78c-f324-4496-897b-73912a7f3d64)

### Table of Contents

1. [Project Overview](project-overview)
2. [Data Source](#data-source)
3. [Tools Used](#tools-used)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Conclusion](#conclusion)

### Project Overview

The Superstore Data Analysis project utilized a dataset from Kaggle to perform comprehensive data processing and analysis using various AWS services. The project began by filtering the order_date column to create separate files for specific dates, which were then uploaded to an Amazon S3 bucket. AWS Glue was used to create a database and a crawler to index the data, combining tables from multiple dates. AWS Athena facilitated querying the consolidated data, and AWS QuickSight was employed for data visualization. This project demonstrates the integration of AWS services for efficient data handling, processing, and visualization to derive actionable insights from the superstore dataset.

### Data Source

Superstore Sales Data: A dataset from [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) containing sales information for a retail superstore. The dataset includes details on orders, dates, products, sales, and customer information.

### Tools Used

- AWS IAM - Used to create and manage AWS users and permissions.
- Amazon S3 - Storage service used for storing and organizing the dataset files.
- AWS Glue - ETL service used to create a database, crawler, and tables from the S3 data.
- AWS Athena - Query service used to perform SQL queries on the final table created by AWS Glue.
- AWS QuickSight - Business intelligence service used for data visualization and creating insights from the dataset.

### Exploratory Data Analysis

- Data Profiling - Analyzed basic statistics for key variables in the dataset, such as sales, profit, and order quantity.
- Time-Based Analysis - Examined trends over the dates, including daily sales and order volumes for the specific dates 2017-01-01 and 2017-01-02.
- Sales and Profit Analysis - Assessed total sales and profit margins, identifying any significant variations between different dates and regions.
- Geographical Analysis - Investigated sales performance by region and city to pinpoint areas with the highest and lowest sales.
- Customer Insights - Analyzed order data to identify key customer segments and purchasing behaviors.
- Visualization - Utilized AWS QuickSight to create visualizations, including charts and graphs, to reveal patterns and insights in the data.

### Conclusion

This project demonstrates the effective use of AWS services for managing and analyzing a retail dataset. By leveraging AWS S3 for storage, AWS Glue for data cataloging and ETL operations, AWS Athena for querying, and AWS QuickSight for visualization, a comprehensive analysis was performed on the Superstore dataset. The results provided valuable insights into sales performance, profitability, and customer preferences across different cities, product categories, and shipping modes. These findings can guide strategic decisions to enhance sales, optimize inventory, and improve overall customer satisfaction.
