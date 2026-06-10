# Ecommerce Purchase Analysis

A Python-based Exploratory Data Analysis (EDA) project that dissects an e-commerce transactions dataset containing 10,000 customer records. This project focuses on cleaning, querying, and identifying core consumer purchase patterns, demographics, and transactional behaviors using the `pandas` library.

---

## 📌 Project Overview
The primary goal of this project is to extract actionable business insights from consumer checkout data. The notebook processes customer interaction touchpoints to uncover key trends such as optimal transactional times, high-value orders, customer occupation distribution, and email domain usage.

## 📊 Dataset Features
The analysis is conducted on `Ecommerce Purchases.csv`, which consists of 10,000 rows and 14 distinct columns:
* **Address:** Billing and shipping address of the user.
* **Lot:** Specific warehouse/lot code.
* **AM or PM:** Time block of the transaction.
* **Browser Info:** User agent string detailing the browser and OS used.
* **Company:** Employer/Organization of the customer.
* **Credit Card:** Customer card number.
* **CC Exp Date:** Credit card expiration date.
* **CC Security Code:** 3 or 4-digit CVV security code.
* **CC Provider:** Financial service provider (Visa, Mastercard, Amex, JCB, etc.).
* **Email:** Customer email address.
* **Job:** Profession of the purchaser.
* **IP Address:** Network address from which the purchase originated.
* **Language:** Language setting of the client browser.
* **Purchase Price:** The total cost of the transaction in USD ($).

---

## 🔍 Key Findings & Analytical Insights

* **Purchase Price Metrics:** The average purchase amount centers around \$50.35, spanning across a range from \$0.00 to a maximum of \$99.99.
* **Time Distribution:** Checkouts are distributed almost evenly throughout the day, showing 4,932 transactions in the AM and 5,068 transactions in the PM.
* **Top Consumer Demographics:**
  * **Language:** German (`de`) and Russian (`ru`) represent the most frequent language segments (1,155 entries each).
  * **Profession:** Interior and Spatial Designers (31) and Lawyers (30) emerge as the top purchasing demographics.
* **Email Provider Dominance:** Email extraction reveals that legacy consumer platforms dominate the landscape:
  1. Hotmail (`hotmail.com`): 1,638 users
  2. Yahoo (`yahoo.com`): 1,616 users
  3. Gmail (`gmail.com`): 1,605 users
* **Targeted Queries:** The analysis includes advanced data filtering, tracking specific card networks (e.g., finding 39 American Express purchases above \$95) and locating expiring credit cards (1,033 cards set to expire in the year '25).

---

## 🛠️ Tech Stack & Dependencies
* **Language:** Python 3.x
* **Data Processing:** Pandas
* **Environment:** Jupyter Notebook

## 🚀 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/ecommerce-purchase-analysis.git](https://github.com/your-username/ecommerce-purchase-analysis.git)
   cd ecommerce-purchase-analysis
