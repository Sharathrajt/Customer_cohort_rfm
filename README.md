# Customer Cohort Segmentation using RFM Analysis

## Project Overview
This project focuses on segmenting customers based on their purchasing behavior using the RFM (Recency, Frequency, Monetary) analysis technique. The goal is to identify different customer segments and devise strategies to enhance customer engagement and retention. The analysis is implemented in Python, and the results are visualized to provide insights into customer segments.

## Data Description
The dataset used for this project contains customer transaction data with the following columns:
- **CustomerID:** Unique identifier for each customer.
- **Recency:** Number of days since the customer's last purchase.
- **Frequency:** Total number of purchases made by the customer.
- **Monetary:** Total monetary value of the customer's purchases.
- **R:** Recency score based on RFM analysis.
- **F:** Frequency score based on RFM analysis.
- **M:** Monetary score based on RFM analysis.
- **RFMgroup:** Combined RFM score.
- **RFM_score:** Total RFM score.
- **Loyalty level:** Segment based on RFM score (e.g., Diamond, Platinum, Gold, Silver).

## Methodology
The project follows these steps:
1. **Data Collection:** Gather customer transaction data.
2. **Data Preprocessing:** Clean the data, handle missing values, and prepare it for analysis.
3. **RFM Analysis:** Calculate RFM scores for each customer.
   - **Recency (R):** Number of days since the last purchase.
   - **Frequency (F):** Number of purchases made.
   - **Monetary (M):** Total amount spent.
4. **Segmentation:** Segment customers based on their RFM scores into categories like Diamond, Platinum, Gold, and Silver.
5. **Visualization:** Create visualizations to depict the distribution of customers across different segments.

## Analysis
The analysis includes:
- Calculation of RFM scores for each customer.
- Segmentation of customers into different cohorts based on their RFM scores.
- Visualization of the number of customers in each segment.
- Strategies for each customer segment to improve engagement and retention.

### Customer Segments
- **Diamond:** Highest value customers with recent, frequent purchases and high monetary value.
- **Platinum:** High value customers with less frequency or recency compared to Diamond.
- **Gold:** Moderate value customers with varying frequency and recency.
- **Silver:** Lower value customers with infrequent purchases and lower monetary value.

### Strategies for Each Segment
- **Diamond:**
  - Reward loyalty with exclusive perks and personalized recommendations.
  - Provide VIP content and exceptional customer service.
- **Platinum:**
  - Implement loyalty programs and referral incentives.
  - Maintain regular, personalized communication.
- **Gold:**
  - Offer premium services and exclusive offers.
  - Focus on upselling and cross-selling relevant products.
- **Silver:**
  - Conduct win-back campaigns and send reminders about benefits.
  - Use limited-time offers to create urgency.

## Results
The RFM analysis revealed the distribution of customers into the four segments:
- **Diamond:** 416 customers
- **Platinum:** 380 customers
- **Gold:** 1051 customers
- **Silver:** 477 customers

These insights help in tailoring marketing strategies and improving customer relationship management.


