# Aviation Safety Analysis (1962–2023)

## 📌 Project Overview

This project is part of the Phase 1 Data Science Code Challenge. It analyzes historical aviation accident data from the National Transportation Safety Board (NTSB) between 1962 and 2023. The primary goal is to identify *low-risk aircraft* types to inform a business expanding into the aviation industry.

## 🎯 Objectives

- Clean and prepare the aviation accident dataset.
- Conduct Exploratory Data Analysis (EDA) to uncover trends and risks.
- Identify aircraft types with lower fatal accident records.
- Create visualizations to support conclusions.
- Present findings via Tableau and slides.

---

## 🗃️ Dataset Information

- *Source*: National Transportation Safety Board (NTSB)
- *Filename*: Aviation_Data.csv
- *Timeframe*: 1962–2023
- *Key Features Analyzed*:
  - Make, Model, Aircraft Category
  - Number of Engines, Engine Type
  - Fatalities, Injuries, Purpose of Flight, Country

---

## 🧹 Data Cleaning

### Steps Performed:
1. Dropped irrelevant or high-missing-value columns:
   - Event.Id, Publication.Date, Airport.Name, Weather.Condition, Location, etc.
2. Handled missing values:
   - Dropped rows missing crucial fields (Make, Model, Aircraft.Category, Total.Fatal.Injuries).
   - Replaced missing values in Purpose.of.Flight with "Unknown".
3. Renamed columns for consistency.
4. Converted data types where needed.

---

## 📊 Exploratory Data Analysis (EDA)

### Key Findings:

- *Most Common Aircraft*:  
  - The most frequently involved aircraft in accidents makes include Cessna and piper

- *Fatal Injuries by Aircraft*:
  - Some aircraft types are involved in higher fatality counts.
  - Aggregated total fatalities by aircraft types helped identify risk trends.

- *Purpose of Flight Trends*:
  - Accidents often occurred during arrial application, arial observation, business and ferry, instructional flights, and unknown-purpose operations.

-

## ✅ Low-Risk Aircraft Identification

By analyzing tleast aircraft types by accident number, the following were *relatively low-risk aircraft* based on historical data: 1st Frt Gp FOCKE - WULF1, 3 XTRIM 450 ULTRA, RIVERS LLC SQ-2, 67 flyig Dutchman d1/LF, 107.5 Flying Corporation, 177 MF LLC PITTS MODEL, 777 FFZ, 2000 Mccoy Genesis, 2007, Savage Air LLC EPIC, 781569 INC FX210



## 📈 Visualizations

Created using *Tableau Public*, including:

- Trend of accidents per year
- Bar chart for Top 10 most common aircraft in accidents
- Bar chart for Least 10 Aircrat types by number of accidents
- bar chart for Injuries by aircraft types
- Bar Fatal injuries by aircraft types
- Bar chart showing distribution of Purpose of Flight.
- Disribution of accident by location.

🔗 [Tableau Public Link (link)](https://public.tableau.com/authoring/James_Ouma/Accidentovertimeyearlytrend/Aviation_Dashboard%203#1)
