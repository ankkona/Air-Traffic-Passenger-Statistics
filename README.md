# Air Traffic Passenger Statistics

This project analyzes **air traffic passenger data** to uncover trends in passenger volume, growth patterns, airline contribution, and travel behavior over time.
The goal is to simulate a **real-world airport analytics dashboard** using **Microsoft Excel**, focusing on **clean data modeling, KPI design, and business storytelling**, not just visuals.

# Dataset
Source : <a href ="https://catalog.data.gov/dataset/air-traffic-passenger-statistics"> Publicly available air traffic passenger data sourced from data.gov</a>

# Tools & Techniques Used

- Microsoft Excel
- Power Query
- Pivot Tables & Pivot Charts
- Excel Data Model
- DAX Measures
- Slicers

# Dashboard
<img src="https://github.com/ankkona/Swiggy-Restaurant-Performance-Pricing-Analysis/blob/main/Dashboard.png" width="1200"/>

# Key Business Questions 

1. **How has total passenger traffic changed over time?**
2. **What is the Year-over-Year growth trend in passenger volume?**
3. **What proportion of passengers are International vs Domestic?**
4. **How is passenger traffic distributed across months (seasonality)?**
5. **Which airlines contribute the most to total passenger traffic?**
6. **How did passenger traffic behave during the COVID period compared to other years?**
7. **What type of passenger flow dominates the airport (Enplaned, Deplaned, Thru/Transit)?**

# Key Insights

* Passenger traffic has not grown consistently over time. Total passenger numbers increased in some years, but dropped sharply during 2020–2021 due to COVID, followed by a gradual recovery in later years.
* YoY % clearly highlights years of decline during COVID and strong rebound growth afterward, proving that passenger traffic is highly sensitive to external events.
* Domestic travel contributes the majority of passenger volume, while International passengers form a smaller but important share.
* Passenger traffic follows clear monthly seasonality. Certain months consistently show higher passenger volumes, indicating peak travel seasons, while others remain comparatively low.
* The Top 5 airlines account for a large portion of total passengers, showing that traffic is concentrated among key carriers.
* COVID caused a clear structural break in passenger trends. Passenger volumes in 2020 and 2021 dropped significantly compared to previous years, making the COVID impact visible even without additional filters.
* Enplaned passengers form the largest passenger activity. Boarding passengers contribute the highest share, followed by deplaned passengers, while transit passengers form a relatively small portion.

# Limitations

* No ticket price or revenue data (so financial analysis is not possible).
* No route or city-pair information.
* YoY values may not appear for months where previous-year data is missing.
  
# Expected Business Impact

* Helps airport management **monitor demand trends** and plan capacity.
* Supports **airline partnership and negotiation decisions**.
* Enables identification of **seasonal peaks** for staffing and resource planning.
* Demonstrates a scalable analytics framework adaptable to Power BI or SQL-based pipelines.

# Future Improvements

* Migrate the model to **Power BI** for scalability.
* Add **route-level or city-pair analysis**.
* Incorporate **revenue and load factor metrics**.
* Automate data refresh using scheduled data pipelines.
* Add forecasting using time-series methods.



