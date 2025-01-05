# Hotel_Booking_Insights_Uncovering_the_Trends


## **Problem Statement**

Have you ever wondered when the ideal time is to book a hotel room? Or how long you should stay to get the best daily rates? What if you wanted to predict whether a hotel might receive an unusually high number of special requests? This hotel booking dataset can help answer these questions. The dataset contains booking details for two types of hotels: **City Hotel** and **Resort Hotel**. It includes key information such as booking dates, length of stay, guest details (number of adults, children, babies), available parking spaces, and more. All personally identifiable information has been removed, making it ideal for analysis. Explore the dataset to uncover important factors that influence hotel bookings.

---

## **Business Objective**

The primary goal of this project is to analyze the booking data from both **City Hotel** and **Resort Hotel**. By extracting valuable insights, we can identify the factors that significantly impact hotel bookings and help the business make data-driven decisions. This project aims to:

- Understand the trends and patterns affecting bookings.
- Identify the best periods to maximize revenue.
- Assess guest preferences and improve services.

---

## **Project Summary**

* This analysis focuses on a dataset that includes bookings for two hotel types: **City Hotel** and **Resort Hotel**.

* The dataset consists of **119,390 rows** and **32 columns** of data.

* Columns in the dataset are categorized into three data types: **Object**, **float64**, and **int64**.

* The dataset includes **duplicates** and **missing values**, which were handled during the data cleaning process. Missing values were replaced, and duplicate rows were removed.

* The **Company** column had the most missing values, followed by the **Agent**, **Country**, and **Children** columns. While the **Children** column only had 4 missing values, the **Company** column had a significant number of **112,593** missing entries.

* To facilitate the analysis, the project workflow was divided into three main stages:
    1. **Data Collection** – Initial exploration of the dataset.
    2. **Data Cleaning & Manipulation** – Addressing missing values, duplicates, and correcting data types.
    3. **Exploratory Data Analysis (EDA)** – Extracting insights through data visualization and analysis.

* In the **Data Collection** phase, basic functions (e.g., `head()`, `tail()`, `info()`, `describe()`, `columns()`) were used to explore and understand the dataset structure.

* During the cleaning phase, the number of unique values in each column was checked, and any columns with incorrect data types were corrected. For instance, new columns like **'total_people'** and **'total_stay'** were added.

* Duplicates were identified and removed—**31,994** duplicate rows were dropped from the dataset.

* Rows where the combined values of **adults**, **babies**, and **children** were all zero were removed, as they represented invalid bookings.

* The **'reservation_status_date'** column, initially an object type, was converted to a date type for better functionality.

* Once data wrangling was completed, the dataset was ready for visualization and analysis.

---

## **Solution to Business Objective**

1. **Boosting Revenue and Business Growth**: To drive hotel growth, it’s essential to focus on factors such as revenue generation, customer satisfaction, and employee retention. Insights derived from data can provide actionable recommendations to improve these areas.

2. **Revenue Generation Insights**: By visualizing the months with the highest revenue, businesses can identify peak booking periods and plan for these seasonal surges.

3. **Optimizing Room Types and Booking Months**: Data visualization revealed the most preferred room types and the best months for hotel visits, offering guidance on optimal room allocation and pricing.

4. **Understanding Guest Preferences**: The analysis highlighted guests' preferences, such as the demand for specific meal types (e.g., **BB - Bed & Breakfast**) and essential services like parking. These insights help hotels tailor their offerings.

5. **Proactive Business Planning**: By understanding guest behavior and preferences, hotels can proactively address potential issues, improve services, and reduce customer complaints in the long run.

6. **Gathering Guest Feedback**: Regular feedback from guests ensures the hotel can continuously improve its services, leading to higher guest satisfaction and increased loyalty.

7. **Attracting Repeat Guests**: Offering periodic promotions and loyalty incentives can help retain old customers and boost the number of repeat bookings.

---

## **Conclusion**

1. **City Hotels** are the preferred choice for guests, making them the busiest hotel type compared to Resort Hotels.

2. **Revenue Generation**: City Hotels have a higher **Average Daily Rate (ADR)** compared to Resort Hotels, resulting in higher revenue.

3. **Stay Duration**: The length of stay is positively correlated with **ADR**. Longer stays lead to higher revenue and ADR.

4. **Guest Retention**: The rate of **repeated guests** is low, with only **3.9%** revisiting. This suggests a need to improve customer retention strategies.

5. **Parking Demand**: A very small percentage of guests (around **8.4%**) require car parking, meaning limited parking space doesn’t significantly affect the business.

6. **Preferred Meal Type**: The most popular meal plan is **BB (Bed & Breakfast)**, which indicates guests' preference for simpler meal options.

7. **Distribution Channels**: Both **Direct** bookings and **TA/TO (Travel Agents/Tour Operators)** have a similar contribution to ADR across both hotel types. However, **GDS (Global Distribution Systems)** significantly influences ADR for **City Hotels**.

8. **Stay Length Preferences**: In both **City** and **Resort Hotels**, the optimal length of stay is less than 7 days. Stays longer than a week see a drastic decline.

9. **Peak Booking Months**: The highest number of bookings occur in **July** and **August**, indicating that these months are particularly popular for hotel visits.

10. **Booking Channels**: The most widely used booking channel is **TA/TO**, accounting for **79.1%** of all bookings.

11. **ADR by Month**: **Resort Hotels** generally see higher ADR in **June, July, and August** compared to **City Hotels**.

12. **Cancellation Rate**: Approximately **27.5%** of bookings are canceled, highlighting a need for better cancellation policies.

13. **Room Type Preferences**: **Room Type 'A'** is the most preferred room type among guests.

---
