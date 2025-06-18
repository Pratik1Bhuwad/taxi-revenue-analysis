# Maximizing Revenue for Drivers: Hypothesis Testing & Taxi Payment Analysis

This project analyzes NYC Taxi trip data to determine whether the type of payment (card vs. cash) affects the fare amount. Using hypothesis testing and exploratory data analysis, we identify customer behaviors and propose strategies to help taxi drivers increase their revenue.

---

##  Project Objective

To investigate the relationship between total fare amount and payment method using hypothesis testing, and to provide actionable recommendations that can help maximize revenue for drivers.

---

##  Dataset Overview

We used cleaned NYC Taxi Trip Records with the following key features:
- `passenger_count` (1 to 5)
- `payment_type` (card or cash)
- `fare_amount`
- `trip_distance` (in miles)
- `duration` (in minutes)

---

## 🔍 Research Question

**Is there a significant difference in average fare between card and cash payment methods?**

---

##  Hypothesis Testing

- **Null Hypothesis (H₀):** There is no difference in average fare between card and cash payments.
- **Alternative Hypothesis (H₁):** There is a difference in average fare between card and cash payments.

✅ Result: The null hypothesis was rejected with a **T-statistic of 165.5** and a **p-value < 0.05**, indicating a significant difference in fare amounts.

---

##  Key Findings

- **Card Payments:** Higher average fare and trip distance.
- **Preference:** 67.5% of all transactions were made using cards.
- **Passenger Count:** Single-passenger rides dominate both payment types.

---

## 💡 Recommendations

- Promote credit card payments to boost fare revenue.
- Offer incentives or discounts for card users.
- Ensure seamless, secure card payment experiences for passengers.

---

## 📁 Files Included

- `MAXIMIZING REVENUE FOR DRIVERS.ipynb` – Jupyter Notebook with full analysis
- `Taxi_Payment_Analysis_Presentation.pptx` – Summary presentation for reporting insights

---

## 🛠 Tools Used

- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Hypothesis Testing (t-test)



⭐️ Give this repo a star if you found it helpful!
