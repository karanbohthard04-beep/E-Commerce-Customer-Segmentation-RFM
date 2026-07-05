# E-Commerce Customer Segmentation using RFM Analysis

## 📌 Project Overview
This project analyzes transactional data from an e-commerce store to segment customers based on their purchasing behavior using the **RFM (Recency, Frequency, Monetary)** model. The goal is to identify high-value customers, loyal users, and customers at risk of churning, enabling the marketing team to run targeted campaigns.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:** Pandas, NumPy, Datetime

## 📊 Methodology (RFM Framework)
- **Recency (R):** Days since the last purchase.
- **Frequency (F):** Total number of purchases made by the customer.
- **Monetary (M):** Total money spent by the customer.

Customers were assigned scores from 1 to 5 for each metric using quantiles, resulting in a final behavioral segmentation:
- **VIP / Champions:** Highest spenders who buy frequently and recently.
- **Loyal Customers:** Regular buyers who respond well to promotions.
- **Potential Loyalists:** Recent buyers with average frequency.
- **At Risk / About to Sleep:** Customers who haven't purchased recently and need re-engagement.
- **Hibernating / Lost:** Low frequency, low spenders who haven't returned in a long time.

## 📈 Business Insights & Actions
- **VIP Customers:** Reward them with exclusive previews, loyalty points, and no-discount premiums.
- **At Risk Customers:** Send personalized email campaigns with special discounts to win them back.
- **Hibernating:** Focus minimal marketing budget here, or send automated re-activation surveys.
