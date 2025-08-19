📊 UPI Transactions Analysis Dashboard (Tableau)
📌 Project Overview

This project focuses on analyzing UPI (Unified Payments Interface) transactions using Tableau.
The goal was to identify key patterns in digital payments across age groups, payment methods, merchants, and cities. The dashboard provides interactive filters to help users drill down into the data and extract meaningful insights.

🎯 Objectives

To analyze the volume of UPI transactions across different dimensions.

To compare transaction patterns across payment methods (Phone Number, QR Code, UPI ID).

To identify popular merchants (Amazon, Flipkart, Swiggy, Zomato, IRCTC) receiving UPI payments.

To track transactions by city with a geographic map visualization.

To enable interactive exploration using filters such as bank name, currency, device type, payment mode, and purpose.

📂 Dataset Description

The dataset used contains UPI transaction details with the following key attributes:

Bank Name Received – Bank handling the transaction.

Currency – Currency used in the transaction.

Device Type – Type of device (Mobile/Desktop).

Payment Mode – Method of payment (Phone Number, QR Code, UPI ID).

Purpose – Reason for transaction (Shopping, Food, Travel, etc.).

Age Group – Grouped as A1, A2, A3.

Merchant – Amazon, Flipkart, IRCTC, Swiggy, Zomato.

City – Location of transaction.

Transaction Volume – Number of transactions.

📊 Dashboard Features

The Tableau dashboard consists of the following sections:

Filters (Top Section)

Bank Name Received

Currency

Device Type

Payment Mode

Purpose

👉 These allow users to dynamically filter and explore the dataset.

Number of Transactions by Age Group

Age Group A1: 3,000 transactions

Age Group A2: 5,000 transactions

Age Group A3: 12,000 transactions

Insight: Younger users (A3) dominate UPI transactions.

Total Transactions by Payment Method & Merchant

Visualizes how Phone Number, QR Code, and UPI ID are used across merchants.

Example: Amazon and Flipkart lead in UPI ID transactions, while Swiggy and Zomato are strong in QR Code payments.

Total Transactions by City (Map)

A geographic map showing transaction density across cities.

Hyderabad recorded the highest transactions (4.9M+), making it the top-performing city.

🔑 Key Insights

Age Group A3 (young adults) contributes the majority of UPI transactions.

UPI ID is the most popular payment method, especially for e-commerce merchants like Amazon & Flipkart.

Food delivery apps (Swiggy & Zomato) receive higher QR code-based payments.

Hyderabad stands out as the city with the maximum transactions.

Interactive filters provide flexibility to analyze specific scenarios (e.g., by bank or purpose).

🛠️ Tools & Technologies

Tableau – For data visualization and dashboard design.

Excel / CSV Dataset – For transaction data storage and preprocessing.

🚀 How to Use

Download the Tableau workbook (.twb or .twbx) file.

Open it in Tableau Desktop / Tableau Public.

Use the filters to explore transaction insights across different dimensions.

📸 Dashboard Preview

<!-- Replace with actual path or GitHub image link -->

📌 Future Improvements

Add trend analysis (month-wise/year-wise transaction growth).

Include customer segmentation based on behavior.

Add average transaction value (ATV) along with count.

Deploy dashboard on Tableau Public for online access.
