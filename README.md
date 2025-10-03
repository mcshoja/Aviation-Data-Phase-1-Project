# Aviation Safety Risk Analysis: Identifying Low-Risk Aircraft Models

## Overview  
This project analyzes aviation accident data from the National Transportation Safety Board (NTSB) covering **1962–2022**. The goal is to provide actionable insights into aircraft safety to support informed decisions on aircraft acquisition for both commercial and private operations.  

---

## Business Understanding  
The company is diversifying into the aviation sector but lacks prior knowledge of aircraft safety risks. Key business questions include:  

- Which aircraft models demonstrate the lowest accident and fatality rates?  
- What operational or environmental factors most strongly influence accident severity?  
- How have safety outcomes changed over time due to regulations and technology?  

**Stakeholder**: Head of the new aviation division  
**Objective**: Identify the safest aircraft options and risk factors to guide acquisition decisions.  

---

## Data Understanding and Analysis  

### Source of Data  
The dataset comes from the **NTSB Aviation Accident Database**, filtered to events between **2000–2022** for modern relevance.  

### Description of Data  
- ~88,000 records of accidents/incidents  
- Features: Aircraft make/model, engines, purpose of flight, weather, flight phase, injury severity  
- New metrics created: **Severity Index** and **Fatality Rate**  
- Data cleaning included: standardizing categories, handling missing values, and removing duplicates  

---

## Visualizations  

### 1. Accident Trends Over Time  
Accidents and fatalities show a declining trend since 2000, largely due to regulatory improvements and technology.  

![Accidents vs Fatalities Over Time](https://github.com/mcshoja/Aviation-Data-Phase-1-Project/blob/dec0607447679aba8345589d8755e0b5731f50e3/accidents%20vs%20fatalities.png)

---

### 2. Lowest-Risk Aircraft Models  
Boeing 737-800 and Embraer E75 consistently demonstrate low severity and minimal fatalities, making them strong candidates for acquisition.  

![Top 10 Lowest-Risk Aircraft Models](https://github.com/mcshoja/Aviation-Data-Phase-1-Project/blob/main/low%20risk%20aricraft%20models.png?raw=true)  

---

### 3. Operational and Environmental Risk Factors  
Weather and flight phase are critical risk drivers. IMC (instrument conditions) during approach and landing shows the highest severity.  

![Weather and Flight Phase Risk](https://github.com/mcshoja/Aviation-Data-Phase-1-Project/blob/main/weather%20conditions.png?raw=true) 

---
### Interactive Dashboard
**View the dashboard:** [Aviation Safety Dashboard](https://public.tableau.com/app/profile/jasho.kiplangat/viz/Aviation_17593475384010/WeatherConditions?publish=yes)

[![Dashboard preview](images/dashboard_thumb.png)](https://public.tableau.com/app/profile/jasho.kiplangat/viz/Aviation_17593475384010/WeatherConditions?publish=yes)

---

## Conclusion  

### Key Findings  
- Accident and fatality rates have steadily declined since 2000.  
- **Boeing 737-800** (commercial) and **Embraer E75** (regional/private) are consistently safest aircraft models.  
- Adverse weather (IMC) and critical phases (approach/landing) strongly influence accident severity.  

### Recommendations  
- Prioritize acquisition of **Boeing 737-800** and **Embraer E75** for safer operations.  
- Favor **commercial operations** over general aviation, which has higher severity and fatalities.  
- Incorporate **weather and phase-of-flight risk data** into pilot training and operational planning.  
