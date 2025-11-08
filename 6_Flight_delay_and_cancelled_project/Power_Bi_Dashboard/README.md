# ✈️ Flight Delay & Cancellation Dashboard (2019–2023)

## 📖 Overview
This Power BI Dashboard analyzes **U.S. Flight Data from 2019 to 2023**, helping visualize flight performance, delays, and cancellations across different airlines.  
The goal is to identify **patterns, causes, and performance trends** to assist airlines in improving efficiency and reducing delays.

---

## 📸 Dashboard Preview
![Dashboard_Preview](6_Flight_delay_and_cancelled_project/images/Flight_data_dashboard.gif)
---

## 🧠 Key Insights
- Visualized **Total Flights**, **Cancelled Flights**, **Successful Flights**, **Delayed Flights**, and **Diverted Flights**.  
- Analyzed delay causes — **Carrier**, **Air System (NAS)**, **Weather**, and **Security**.  
- Built **seasonal visualizations** (Winter, Spring, Summer, Fall) instead of standard quarters to highlight weather-related impacts.  
- Incorporated **drill-through and drill-down** features for detailed exploration.  
- Added **timeline slicers** for filtering delayed and cancelled flights by custom date ranges.  
- Displayed **average delay times**, **major delay causes**, and **cancellation reasons**.  
- Created **city-level analysis** to identify top origins and destinations for each airline.

---

## 🛠️ Tools & Techniques Used
- **Power BI**
  - Data Modeling  
  - DAX Measures  
  - Drill-through & Drill-down  
  - Interactive Slicers  
  - Time Intelligence
- **Dataset:** U.S. Flight Data (2019–2023) (https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023/data?select=flights_sample_3m.csv)

- **Data Cleaning:** Performed in Python and Power Query

To see complete code, check out: ['Dashboard_data_filteration'](6_Flight_delay_and_cancelled_project/3_Dashboard_Data_preporation.ipynb)

---

## 📊 Dashboard Features
### 🧩 Cards
- **Total Flights**
- **Cancelled Flights**
- **Successful Flights**
- **Delayed Flights**
- **Diverted Flights**

### 📈 Visuals & Charts
- Bar charts showing **delay causes** (Carrier, NAS, Weather, Security).  
- Yearly, monthly, and **seasonal trends** for flight performance.  
- Visuals showing **average delay duration** by airline and reason.  
- **City-based analysis** of flight origins and destinations.  
- Drill-down visuals to analyze **delay and cancellation variations** over years, months, and seasons.

### 🔍 Filters & Interactions
- **Airline Slicer:** Select any airline to view detailed performance.  
- **Timeline Slicers:** Separate slicers for delayed and cancelled flights.  
- **Drill-through pages:** Explore in-depth airline statistics and specific flight details.  

### 📋 Data Tables
- Detailed tables showing **delayed** and **cancelled** flights with:
  - Flight Number  
  - Origin & Destination Cities  
  - Date & Delay Duration  

---

## 💡 Purpose
This dashboard helps:
- **Airlines** identify operational inefficiencies and major delay causes.  
- **Analysts** understand temporal and seasonal patterns affecting flight reliability.  
- **Decision-makers** plan better scheduling and maintenance strategies.

---

## 🏁 Results
- Clear visibility into flight performance trends over five years.  
- Identification of **dominant delay causes** by airline and season.  
- Seasonal insight into **weather’s impact** on flight delays.  
- Quick exploration of cancelled and delayed flights through **interactive visuals**.

---

## 📂 How to View
1. Download the `.pbix` file from this repository.  
2. Open it in **Power BI Desktop**.  
3. Explore visuals using slicers and drill-through options.

---


## 🧑‍💻 Author
**Muhammad Ahmed**  
_Data Analyst | Power BI | Python | SQL | Excel_  
📧 [raoahmadhnd76@gmail.com](mailto:raoahmadhnd76@gmail.com)  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/ahmedtheanalyst )

---

## 🏷️ Tags
`#PowerBI` `#DataAnalytics` `#DataVisualization` `#Dashboard` `#FlightData` `#BusinessIntelligence` `#DataAnalysis`

