# Air Traffic Passenger Statistics

This project analyzes **air traffic passenger data** to uncover trends in passenger volume, growth patterns, airline contribution, and travel behavior over time.
The goal is to simulate a **real-world airport analytics dashboard** using **Microsoft Excel**, focusing on **clean data modeling, KPI design, and business storytelling**, not just visuals.

## 🧰 Tools & Techniques Used

- Microsoft Excel
- Power Query
- Pivot Tables & Pivot Charts
- Excel Data Model
- DAX Measures

## Key Business Questions 

1. **How has total passenger traffic changed over time?**
2. **What is the Year-over-Year growth trend in passenger volume?**
3. **What proportion of passengers are International vs Domestic?**
4. **How is passenger traffic distributed across months (seasonality)?**
5. **Which airlines contribute the most to total passenger traffic?**
6. **How did passenger traffic behave during the COVID period compared to other years?**
7. **What type of passenger flow dominates the airport (Enplaned, Deplaned, Thru/Transit)?**

---

## 📈 Key KPIs Tracked

* **Total Passengers**
* **YoY Passenger Growth (%)**
* **International Passenger Share (%)**
* **Monthly Passenger Trend**
* **Top 5 Airline Contribution**
* **Passenger Flow Mix**
* **Seasonality Index (Monthly Heatmap)**

---

## 🔍 Key Insights

* Passenger traffic shows **clear seasonality**, with peak volumes during specific months.
* **Significant decline** in passenger numbers is observed during **COVID years (2020–2021)**, followed by gradual recovery.
* **International passengers form a smaller but strategically important share**, indicating higher revenue and operational complexity.
* A small number of airlines contribute a **disproportionately large share** of total passenger traffic.
* YoY growth trends are **volatile**, highlighting sensitivity to external events and demand fluctuations.

---

## 📌 Dashboard Design Decisions

* **YoY % KPI and line chart are isolated from the Year slicer** to preserve analytical correctness.
* Monthly and yearly trends are separated to avoid over-filtering.
* Slicers are limited to **Year and Region** to balance interactivity and interpretability.
* Not all visuals are KPIs — supporting charts are used for context and storytelling.

---

## ⚠️ Assumptions

* Passenger count data is assumed to be **accurate and consistently recorded**.
* Missing or zero values are treated as **true operational records**, not data errors.
* COVID impact period is defined based on year classification, not exact dates.
* Analysis assumes **one primary airport context**.

---

## 🚧 Limitations

* Dataset does not include **revenue, ticket price, or capacity data**, limiting financial insights.
* No demographic or route-level data (origin–destination pairs).
* YoY analysis for partial years may be less reliable due to missing prior-period data.
* Excel performance may degrade with significantly larger datasets.

---

## 🚀 Expected Business Impact

* Helps airport management **monitor demand trends** and plan capacity.
* Supports **airline partnership and negotiation decisions**.
* Enables identification of **seasonal peaks** for staffing and resource planning.
* Demonstrates a scalable analytics framework adaptable to Power BI or SQL-based pipelines.

---

## 🔧 Future Improvements

* Migrate the model to **Power BI** for scalability.
* Add **route-level or city-pair analysis**.
* Incorporate **revenue and load factor metrics**.
* Automate data refresh using scheduled data pipelines.
* Add forecasting using time-series methods.

---

## 🏁 Conclusion

This project demonstrates **end-to-end data analytics capability in Excel**, from raw data cleaning to advanced KPI modeling and dashboard storytelling.
It reflects **real business constraints**, analytical thinking, and strong command of Excel beyond basic reporting.

---

📁 *This project is part of my analytics portfolio and is intended to showcase practical, job-ready Excel skills.*


<a href ="https://catalog.data.gov/dataset/air-traffic-passenger-statistics">Real Word data< </a>
