# Analytics_projects
Analytics_projects
🛒 E-Commerce Orders Dataset — Data Cleaning Project

![Cleaned Data](./Ayodeji%20cleaned%20data.PNG)

![Raw Dataset](./Ayodeji_Raw%20dataset.PNG)


📋 Overview

This project focuses on cleaning and preparing a raw e-commerce orders dataset for analysis. The dataset contains transactional records including order details, customer information, product types, pricing, shipping, payment methods, and sales outcomes.

📁 Dataset Description
This dataset consist OrderID,Date,CustomerID,Product, Quantity, UnitPrice, ShippingAddress,PaymentMethod, Orderstatus,TrackingNumber,ItemsInCart,Coupocode, ReferralSource, and Totalprice



🧹 Data Cleaning Steps

The following cleaning operations were performed on the raw dataset:

1. Handled Missing Values

	•	Identified columns with null/blank entries across key fields such as CouponCode, ItemsInCart, and ReferralSource.
	•	Filled missing categorical values (e.g., CouponCode) with "N/A" to indicate no coupon was applied.
	•	Filled missing numerical values (e.g., ItemsInCart) using appropriate substitution strategies (e.g., median or mode).

2. Standardized Formatting

	•	Ensured consistent date formats across the Date column.
	•	Verified that Month and Year columns correctly matched the Date field.
	•	Cleaned up whitespace and inconsistent casing in string columns.

3. Data Type Corrections

	•	Confirmed numeric columns (UnitPrice, TotalPrice, Quantity) were stored as numbers, not strings.
	•	Ensured OrderID and CustomerID were treated as identifiers (string/text type).

🛠 Tools Used

•	Microsoft Excel — data inspection, cleaning, and filling missing values

📊 Potential Use Cases

This cleaned dataset is suitable for:

•	Sales performance analysis
•	Customer segmentation
•	Coupon and referral source effectiveness studies
•	Order status and return rate reporting
•	Revenue trend analysis by product, year, or payment method

🚀 How to Use

1.	Clone or download this repository.
2.	Open the cleaned dataset file (orders_cleaned.xlsx) in Microsoft Excel or any compatible tool.

📌 Notes

1	The raw dataset is included for reference as orders_raw.xlsx.
2	All cleaning was done without removing rows — missing values were filled rather than dropped to preserve the full dataset size.

🤝 Contributing

Feel free to open an issue or submit a pull request if you’d like to suggest improvements to the cleaning methodology or add further analysis.

📄 License

This project is open source and available under the MIT License.
