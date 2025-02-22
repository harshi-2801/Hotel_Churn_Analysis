# Hotel Churn Analysis

## Project Overview
This project focuses on analyzing hotel booking cancellations for **City Hotel** and **Resort Hotel** to understand the key factors contributing to high churn rates. The objective is to identify trends, customer behaviors, and operational inefficiencies that lead to cancellations and provide actionable insights to reduce churn and improve revenue.

---

## Dataset
- **Source:** Hotel Booking Dataset (2015-2017)
- **Records:** ~119,390 bookings
- **Features:** 36 columns covering customer details, booking information, hotel types, pricing, cancellation status, etc.

---

## Tools & Technologies
- **Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Visualization:** Matplotlib, Seaborn
- **IDE:** Jupyter Notebook / Google Colab
- **Version Control:** Git, GitHub

---

## Exploratory Data Analysis (EDA)
1. **Cancellation Rate Analysis:**
   - Found that ~37% of bookings were canceled, significantly affecting revenue.
   - Higher ADR (Average Daily Rate) correlates with increased cancellations.

2. **Seasonal Trends:**
   - August had the highest bookings and cancellations.
   - January recorded the highest cancellation rate.

3. **Geographic Analysis:**
   - Portugal showed the highest number of cancellations.

4. **Booking Channels:**
   - 46% of bookings were made through Online Travel Agencies (OTAs).
   - Only 4% of bookings were direct, indicating reliance on third-party channels.

---

## Data Cleaning
- Removed personal identifiers (name, email, phone, credit card).
- Handled missing values and corrected data types.
- Aggregated data based on cancellation status, month, and booking channels.

---

## Key Insights
- **Price Sensitivity:** Higher prices lead to more cancellations.
- **Over-reliance on OTAs:** Hotels depend heavily on third-party booking channels.
- **Seasonal Variations:** Specific months like January require targeted marketing due to higher cancellation rates.

---

## Recommendations
1. Optimize pricing strategies to reduce cancellations during high ADR periods.
2. Increase promotions and discounts during high-churn months (e.g., January).
3. Encourage direct bookings through exclusive offers and loyalty programs.
4. Focus on improving services in regions with high cancellations (e.g., Portugal).

