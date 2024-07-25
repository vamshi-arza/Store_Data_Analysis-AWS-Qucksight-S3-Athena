# Superstore Data Analysis Using AWS Services

### Project Architecture 

![proj diag](https://github.com/user-attachments/assets/adfbd78c-f324-4496-897b-73912a7f3d64)

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

