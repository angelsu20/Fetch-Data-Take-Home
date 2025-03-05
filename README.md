# Fetch-Data-Take-Home 

## Overview  
This report provides an in-depth analysis of Fetch’s transactional and user datasets, focusing on **data quality assessment, SQL-based insights, and stakeholder communication**. It evaluates data integrity, identifies trends, and offers actionable recommendations for improving Fetch’s business decisions.   

## Key Sections  

### 1. Introduction  
- **Objective:** Assess data quality, extract business insights, and provide recommendations.  
- **Datasets analyzed:**  
  - `USER_TAKEHOME.csv`: User demographics.  
  - `TRANSACTION_TAKEHOME.csv`: Transaction records.  
  - `PRODUCTS_TAKEHOME.csv`: Product information.  

### 2. Data Quality Assessment  
- **Missing values** identified in key fields such as `BIRTH_DATE`, `STATE`, `LANGUAGE`, `CATEGORY_4`, and `MANUFACTURER`.  
- **Duplicate records** found in `TRANSACTION_TAKEHOME` (171) and `PRODUCTS_TAKEHOME` (215).  
- **Inconsistencies** in `FINAL_QUANTITY` and `FINAL_SALE` fields, indicating potential data entry or processing errors.  
- **Cleaning approach:**  
  - Removed duplicates.  
  - Standardized missing values.  
  - Filtered out incomplete transactions.  

### 3. SQL Analysis & Business Insights  
- **Top brands by receipts scanned & total sales.**  
- **Health & Wellness sales percentage by generation.**  
- **Power users with highest engagement.**  
- **Leading brands in different product categories.**  
- **Year-over-year user growth trends.**  

### 4. Key Findings & Recommendations  
- **Data Integrity Issues:** Inconsistent transaction records need standardization.  
- **Power Users:** Many high-value users are missing from the dataset, requiring further investigation.  
- **Declining User Acquisition:** A **42% decrease in 2023** and **24% decrease in 2024** suggest the need for improved marketing efforts.  
- **Action Items:**  
  - Improve transaction logging and barcode scanning accuracy.  
  - Address missing and inconsistent data.  
  - Refine user engagement and retention strategies.  

### 5. Conclusion  
The report highlights critical **data issues, user trends, and business insights**. It suggests immediate actions to **improve data quality, enhance customer insights, and drive business growth.**  

## Contact  
For further discussions or inquiries, reach out to:  
**Angel Su**  
Email: angel.su1220@gmail.com
