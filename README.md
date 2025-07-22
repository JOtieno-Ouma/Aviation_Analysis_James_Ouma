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
  - The most frequently involved aircraft makes include Cessna, Piper, and Beech.

- *Fatal Injuries by Aircraft*:
  - Some aircraft types are involved in higher fatality counts.
  - Aggregated total fatalities by make and model helped identify risk trends.

- *Purpose of Flight Trends*:
  - Accidents often occurred during personal flights, instructional flights, and unknown-purpose operations.

- *Engine Type*:
  - Single-engine aircraft were more commonly involved in accidents, but not necessarily in fatal ones.

---

## ✅ Low-Risk Aircraft Identification

By analyzing total fatal injuries by aircraft make/model, the following were *relatively low-risk aircraft* based on historical data:

- Models with a high number of incidents but low fatalities.
- Specific single-engine planes used in training and local transport.

Further statistical analysis can refine these findings based on normalization by total flight hours or usage.

---

## 📈 Visualizations

Created using *Tableau Public*, including:

- Bar chart of most common aircraft types.
- Heatmap of fatal injuries by aircraft make.
- Pie chart showing distribution of Purpose of Flight.
- Trend of accidents per year.

🔗 [Tableau Public Link (link)](https://public.tableau.com/)
