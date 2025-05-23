# Hospitality EDA Project 

This project involves end-to-end data preprocessing and exploratory data analysis (EDA) on a hospitality dataset. By merging and cleaning five raw data tables, we build a unified dataset to uncover trends in bookings, customer behavior, room preferences, and revenue performance

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

# 🛠️ Preprocessing

The raw data was distributed across five tables:
- `dim_date.csv`
- `dim_hotels.csv`
- `dim_rooms.csv`
- `fact_aggregated_bookings.csv`
- `fact_bookings.csv`

✅ Goals
- Load and understand individual datasets
- Clean missing and inconsistent values
- Merge fact and dim tables accordingly 

📦 Key Preprocessing Steps
- Converted date columns to proper datetime format
- Removed duplicates and handled null values
- Merged  datasets using common keys (`date`, `room_id`, etc.)
- Generated a dataset with relation

---
# 🛠️ Libraries Used

| Library              | Purpose                                              |
|----------------------|------------------------------------------------------|
| **pandas**           | Data manipulation                                    |
| **numpy**            | Numerical operations                                 |
| **matplotlib.pyplot**| Plotting charts and graphs                           |
| **matplotlib.ticker**| Axis formatting (e.g., currency in thousands)        |
| **seaborn**          | Statistical data visualization                       |
| **warnings**         | To ignore unnecessary output                         |

---
#  📊 Exploratory Data Analysis (EDA)

The merged dataset was thoroughly explored to uncover key patterns and business trends. The analysis focused on:

- 📅 **Seasonality**: Identifying peak booking periods and seasonal trends
- 💰 **Revenue Performance**: Comparing average revenue across weekdays and weekends
- 🏨 **Property Insights**: Ranking properties by total revenue contribution
- 🛏️ **Room Insights**: Evaluating guest capacity and room class preferences
- 📲 **Platform Behavior**: Understanding booking volume across different platforms
- ✅ **Booking Outcomes**: Analyzing confirmation, cancellation, and other booking statuses

Explore detailed visualizations and insights in the [EDA notebook](https://github.com/karan-bodara/advance_hospitality_analysis/blob/main/eda/02_hospitality_eda.ipynb) provided.

---

# 🔑 Key Insights

The exploratory analysis of the hospitality dataset revealed critical business patterns and revenue drivers:

- **📅 Peak Booking Season**  
  Booking activity surges between **May and July**, suggesting strong seasonal demand. Targeted promotions during this period could drive significant gains in occupancy and revenue.

- **💼 Room Class Performance**  
  **Elite-class rooms** generate the highest average revenue and accommodate larger groups, highlighting a customer preference for premium experiences.

- **🏨 Top Performing Properties**  
  Properties like **AtliQ Exotica**, **AtliQ Palace**, and **AtliQ City** consistently lead in revenue contribution, making them prime candidates for further investment or expansion strategies.

- **📈 Weekend vs Weekday Revenue**  
  **Weekends outperform weekdays** by over 20% in average revenue, suggesting higher guest spending during leisure stays and an opportunity to adjust weekend pricing models.

- **📲 Digital Booking Behavior**  
  A large portion of bookings come from **online platforms**, especially the brand's **website and mobile app**, reinforcing the need to enhance digital user experience and streamline the booking process.

- **✅ Booking Confirmation Trends**  
  While a majority of bookings are confirmed, a notable percentage are cancelled, indicating a potential need to review cancellation policies or prepayment structures.
  
- **🏙️ City level Analysis**  
Mumbai outperforms all other cities in **total room revenue**, indicating it as the top-performing city in terms of hospitality demand.
----
# 🧾 Conclusion

This project shows how raw booking and property data can be transformed into meaningful insights for the hospitality industry. It highlights seasonal trends, platform usage, and customer behavior that can inform pricing strategies, inventory management, and marketing focus.

---
## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

---
# 🌟 About Me
As a data enthusiast, I specialize in building efficient data systems, uncovering insights, and solving business problems through data-driven solutions. I’m committed to delivering high-quality, reliable results that add real value to your projects.

Lets connect : [LinkedIn](https://www.linkedin.com/in/karan-bodara-8684562b4/)
