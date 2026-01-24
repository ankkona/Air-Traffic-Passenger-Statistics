# Air Traffic Passenger Statistics

This project analyzes **air traffic passenger data** to uncover trends in passenger volume, growth patterns, airline contribution, and travel behavior over time.
The goal is to simulate a **real-world airport analytics dashboard** using **Microsoft Excel**, focusing on **clean data modeling, KPI design, and business storytelling**, not just visuals.

# Dataset
* Source : <a href ="https://catalog.data.gov/dataset/air-traffic-passenger-statistics"> Publicly available air traffic passenger data sourced from data.gov</a>
* Processed Dataset: <a href ="https://github.com/ankkona/Air-Traffic-Passenger-Statistics/blob/main/Air%20Traffic%20Passenger%20Statistics.xlsx"> Air Traffic Passenger Statistics – Cleaned & Modeled Excel Dataset</a>

# Tools & Techniques Used

- Microsoft Excel
- Power Query
- Pivot Tables & Pivot Charts
- Excel Data Model
- DAX Measures
- Slicers

# What I Worked On

- Cleaned and transformed raw data using Power Query.
- Built an Excel data model and created calculated measures using DAX.
- Designed KPIs such as Total Passengers and Year-over-Year growth.
- Created an interactive dashboard using pivot charts and slicers.

# Dashboard
<img src="https://github.com/ankkona/Air-Traffic-Passenger-Statistics/blob/main/Dashboard.png" width="1200"/>

# Key Business Questions 

1. **How has total passenger traffic changed over time?**
2. **What is the Year-over-Year growth trend in passenger volume?**
3. **What proportion of passengers are International vs Domestic?**
4. **How is passenger traffic distributed across months (seasonality)?**
5. **Which airlines contribute the most to total passenger traffic?**
6. **How did passenger traffic behave during the COVID period compared to other years?**
7. **What type of passenger flow dominates the airport (Enplaned, Deplaned, Thru/Transit)?**

# Key Insights

* Passenger traffic does not grow steadily over time. While some years show growth, total passenger volume dropped sharply in 2020–2021 due to COVID, followed by gradual recovery in later years.
* Year-over-Year (YoY %) analysis clearly highlights the sharp decline during COVID years and the strong rebound afterward, showing that air travel demand is highly sensitive to external events.
* Domestic passengers make up the majority of total traffic, while International passengers form a smaller but strategically important segment.
* Passenger traffic shows clear monthly seasonality. Certain months consistently experience higher volumes, indicating peak travel periods.
* The Top 5 airlines contribute a large share of total passengers, suggesting that airport traffic is concentrated among a few major carriers.
* COVID created a visible break in passenger trends. The impact is evident directly from yearly passenger data without requiring additional filters.
* Among passenger activities, Enplaned (boarding) passengers form the largest share, followed by Deplaned passengers, while Transit passengers account for a much smaller portion.

# Limitations

* No ticket price or revenue data (so financial analysis is not possible).
* No route or city-pair information.
* YoY values may not appear for months where previous-year data is missing.
  
# Expected Business Impact

* Helps airport authorities understand passenger demand trends over time.
* Supports planning for staffing, infrastructure, and peak travel periods.
* Provides insights into airline concentration and passenger composition.
* Demonstrates how Excel can be used for structured data analysis and KPI reporting.

# Future Improvements

* Migrate the model to **Power BI** for scalability.
* Add **route-level or city-pair analysis**.
* Incorporate **revenue and load factor metrics**.
* Automate data refresh using scheduled data pipelines.
* Add forecasting using time-series methods.



