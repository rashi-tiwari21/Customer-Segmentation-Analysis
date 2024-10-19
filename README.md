# Customer Segmentation Analysis

**Description:**  
This project uses RFM (Recency, Frequency, Monetary) analysis to segment customers based on their purchase behavior. The segmentation helps businesses identify key customer groups such as Best Customers, At-Risk Customers, and more. This analysis aids in customer targeting for marketing and retention strategies.

## Features
- Create and populate an RFM table to store customer scores and segments.
- Segment customers based on RFM scores.
- Perform detailed customer behavior and purchasing pattern analysis.
- Identify key customer groups like high spenders, frequent buyers, and at-risk customers.

## Initial Queries

### 1. Create the RFM Table
```sql
CREATE TABLE RFM_Table (
    CustomerID INT PRIMARY KEY,
    Frequency INT,
    Monetary DOUBLE,
    Recency INT,
    Recency_Score INT,
    Frequency_Score INT,
    Monetary_Score INT,
    Customer_Segment VARCHAR(50)
);
