# Hospitality Power BI Project 
An interactive Power BI dashboard analyzing performance data for a multi-city luxury hotel chain. Track KPIs like revenue, occupancy, RevPAR, ADR, guest ratings, and platform efficiency using a dynamic, multi-page report powered by a Galaxy Schema data model. Built for strategic business insights across property, city, and booking channels.

---
# 📌 Problem Statement
- AtliQ Grands is a five-star hotel chain in India operating for 20+ years.
- They are losing market share and revenue in the luxury/business segment. Causes include:

   - Increased competition

   - Ineffective management decisions

- They lack an in-house data analytics team. The company has hired a third-party service provider to:

  - Analyze historical data

  - Provide data-driven insights for strategic improvement

---

# 📁 Dataset

| Table Name               | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| fact_booking        | Transaction-level booking data including platform, guest count, ratings, and check-in details etc |
| fact_aggregated_booking | Pre-calculated metrics such as daily room capacity and successful bookings by property and category |
| dim_hotels          | Hotel metadata including property ID, city, and category classification    |
| dim_rooms         | Room classification details such as room type and category                 |
| dim_date         | Full calendar table with date, month, week         |

---

# 🧱 Data Modeling 
- This project adopts a Galaxy Schema (Fact Constellation) to efficiently organize transactional and aggregated hotel booking data
- All relationships follow optimized many-to-one cardinality

<img width="829" alt="image" src="https://github.com/user-attachments/assets/ff7214e3-dba7-4190-b69b-da556fe245fa" />

---
# 🔍 Features
- Interactive slicers and filters
- Tooltips
- Bookmarks & selections
- Dynamic visualizations (Clustured coloumn chart, Line chart, KPIs etc)
- Textbox & Image
- Custom DAX measures
- Page navigation
- Power Query
- Conditional formatting ..etc
---

## 📈 Insights & Recommendations

### 1. **Overall Business Performance**
- The total revenue across all cities is **₹1.71 billion**, with an **Average Revenue Per Guest** of approximately **₹6,200**.
- The overall **occupancy rate** is **57.9%**, indicating potential to improve room utilization and drive incremental revenue.

> 🔮 **Future Potential**: Even a 10% uplift in occupancy could lead to a revenue increase of ₹2–3 Cr monthly, assuming current ADR holds.

---

### 2. **City-Level Revenue Contribution**
- **Mumbai** dominates with **39% of the total revenue**, driven by high occupancy and ADR.  
- In contrast, **Delhi contributes only 17%**, despite having similar capacity.
- **Hyderabad and Bangalore** show moderate performance but still trail Mumbai by a large margin.

> 📌 **Recommendation**: Consider redistributing marketing budgets and running targeted campaigns in Delhi and Hyderabad to improve yield.

---

### 3. **Room Class Performance**
- **Elite rooms** have the highest booking frequency and contribute the most revenue, while **Presidential rooms**, though fewer in volume, generate maximum revenue per guest due to high ADR (>₹18K).
- **Standard rooms** have low occupancy and generate the least revenue.

> 💡 Bundle or rebrand Standard rooms with limited-time offers to improve occupancy and reduce underutilization.

---

### 4. **Booking Platform Efficiency**
- Online platforms (MakeMyTrip, Tripset) drive significant volume but experience **higher cancellation rates (up to 11%)**.
- **Direct bookings via office** show higher realization % (over 78%), indicating stronger guest commitment and profitability.

> 🏷️ Incentivize direct bookings through loyalty programs or discount codes to improve realization and reduce platform commissions.

---

### 5. **Guest Behavior & Pricing Strategy**
- The **average spend per guest** is around **₹6,200**, a strong indicator of guest willingness to pay in the luxury segment.
- Given the disparity in revenue contribution (**Mumbai at 39% vs. Delhi at 17%**), a **dynamic pricing model** is recommended to maximize revenue per available room.

> 📈 **Actionable Tip**: Use data-driven pricing strategies (based on demand, season, platform, and room class) to optimize profitability across cities.





---











# 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---

# 🌟 About Me
As a data enthusiast, I specialize in building efficient data systems, uncovering insights, and solving business problems through data-driven solutions. I’m committed to delivering high-quality, reliable results that add real value to your projects.

Lets connect : [LinkedIn](https://www.linkedin.com/in/karan-bodara-8684562b4/)















