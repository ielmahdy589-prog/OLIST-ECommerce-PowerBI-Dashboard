# OLIST-ECommerce-PowerBI-Dashboard
Interactive Power BI dashboard analyzing 100K+ orders from Brazil's largest e-commerce platform | DAX Measures | Dark Theme | 4 Pages

## Dashboard Preview

### Executive Overview
![Executive Overview](<img width="2557" height="1431" alt="executive" src="https://github.com/user-attachments/assets/4c479c30-da56-4064-90f8-354d68bbd780" />
)

### Product Analysis
![Product Analysis](<img width="2648" height="1481" alt="product" src="https://github.com/user-attachments/assets/6d3e4f65-91d9-4db8-a4e6-8e685b727934" />
)

### Customer Analysis
![Customer Analysis](<img width="2511" height="1428" alt="customer" src="https://github.com/user-attachments/assets/c7eb7af1-d3cc-4fed-b60f-a84826674530" />
)

### Delivery and Operations
![Delivery and Operations](<img width="2535" height="1405" alt="delivery" src="https://github.com/user-attachments/assets/6b101db9-d15d-4652-8609-08f2ef9b13fd" />
)

---

## Download the Dashboard

The Power BI file is too large to host on GitHub directly.
You can download it from the link below:

Google Drive Link: [https://app.powerbi.com/links/zYOOGeqpsU?ctid=266f6ed8-6f7c-4eb0-80cb-8fe393cea47d&pbi_source=linkSharei](#)

To open the file you need Power BI Desktop, which is free to download from:
https://powerbi.microsoft.com/desktop

---

## What This Dashboard Covers

The dashboard has 4 pages, each focused on a different area of the business.

Executive Overview shows the overall business performance including total revenue, total orders, number of customers, average order value, and average review score. It also shows revenue trends over time and order status breakdown.

Product Analysis focuses on which product categories generate the most revenue and orders. It shows the top 5 categories, monthly revenue trends, and which cities have the most active sellers.

Customer Analysis looks at customer behavior including how many customers come back for a second purchase, the retention rate, average orders per customer, and how review scores relate to revenue.

Delivery and Operations tracks how well the logistics side of the business is performing. It shows on-time delivery rates, late order percentages, average delivery days over time, and which states have the worst delivery performance.

---

## Key Findings

Total revenue across all orders was R$13.59 million.

Health and Beauty was the top performing category with R$1.3 million in revenue.

Sao Paulo accounted for 42 percent of all orders, making it by far the most active region.

The average customer review score was 4.09 out of 5, which indicates strong overall satisfaction.

Delivery performance improved significantly over the 2 years. Average delivery time dropped from around 50 days in early 2017 down to 12 days by 2018, which is a 75 percent improvement.

The customer retention rate was only 3.1 percent, meaning most customers only buy once. This is the biggest area of opportunity for the business.

Revenue peaked in November 2017, which lines up with Black Friday promotions.

Northern states like RR, AP, and AM had delivery times roughly twice as long as southern states, pointing to a clear logistics gap.

---

## Technical Details

The dashboard was built using Microsoft Power BI Desktop.

The data model connects 6 tables together using order ID, customer ID, product ID, and seller ID as the join keys.

Three custom DAX measures were created beyond the default aggregations.

The first measure counts repeat customers, defined as customers with more than one unique order.

The second measure calculates the retention rate by dividing repeat customers by total unique customers.

The third measure calculates total orders at the category level accurately by counting rows from the order items table using a related table function.

A calculated column was also added to translate all product category names from Portuguese into English using a SWITCH statement in DAX.

---

## How to Use

Download the .pbix file from the Google Drive link above.

Open it in Power BI Desktop.

Use the sidebar on the left to navigate between the 4 pages.

Use the Year and Month slicers at the top of each page to filter the data.

---

## Repository Structure

```
OLIST-ECommerce-PowerBI-Dashboard
│
├── README.md
├── screenshots
│   ├── executive.png
│   ├── product.png
│   ├── customer.png
│   └── delivery.png
└── data
    └── (CSV files from Kaggle)
```

---

## Connect with Me

LinkedIn: https://linkedin.com/in/ibrahim-elmahdy
GitHub: https://github.com/ibrahim-elmahdy
