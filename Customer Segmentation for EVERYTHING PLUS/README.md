# Creating Customer Segmentation for EVERYTHING PLUS: An Analysis of Household E-commerce Purchased History
**Analyst: Ica Candra R**<br>
**Discussion Team Members: Jonathan Chan, Zamani**<br>
July 2023<br>
<br>
**Reviewed by Anand Pandey**<br>
*Lead Data Scientist at AirAsia with more than 7 years of experience in data science in various industries, including Aviation, Retail, Automobile and Reinsurance*

[See the presentation](https://drive.google.com/file/d/1ptC5qAuxsKJ8R3n9-RmpL0u196IASoBb/view?usp=drive_link)

## Project Description
This project aims to improve customer segmentation for Everything Plus: Plus a Little Bit More, an e-commerce company specializing in household goods. My team and I developed a new customer segmentation approach by analyzing transaction history data. The new segmentation should enable the company to create more personalized offers for different user groups, leading to a minimum 5% increase in conversion rates, revenue, and user retention.

## Method

To achieve the project objective, the following steps will be taken:

1. **Data Preparation:** <br>
The transaction history data, including attributes such as `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, and `CustomerID`, will be cleaned and preprocessed. This step involves handling missing values, removing duplicates, excluding discount/promo/cancel order/return/postage/other extra services transactions, and transforming the data into a suitable format for analysis.

2. **Exploratory Data Analysis:** <br>
The cleaned data will be explored to gain insights into customer behaviour. This analysis may involve examining patterns in purchase frequency, recency, monetary value, and quantity and identifying any other relevant patterns or trends. This step will also check seasonal impact and the customers' price preferences. 

3. **Statistical Hypotheses Test:** <br>
Check and validate the hypotheses from EDA

4. **Customer Segmentation:** <br>
Three approaches will be considered for customer segmentation: a) RFM (Recency, Frequency, Monetary), b) K-means clustering, and c) RFM combined with K-means. K-means clustering will group customers based on their transactional attributes, while RFM analysis will evaluate customers based on their recency, frequency, and monetary value. These techniques will help identify distinct customer segments with similar characteristics and behaviours.

5. **Evaluation:** <br>
The effectiveness of the new customer segmentation approach will be evaluated based on the success metrics defined earlier. The conversion rate, revenue, and retention will be monitored after implementing the new segmentation. The new segmentation approach will be considered successful if the desired 5% improvement is achieved for each metric, respectively.

6. **Recommendations:** <br>
Based on the analysis results, recommendations will be provided to the Product Manager and the team. These recommendations may include strategies for creating personalized offers, targeting specific customer segments, and refining the segmentation approach further.

## Project At a Glance
