# Bluebikes Urban Mobility Analysis: Optimizing Demand & Sustainable Commuting

## Project Overview
This project analyzes Bluebikes trip data from the Greater Boston area (2023–2024) to understand how urban bike-sharing systems can reduce congestion and promote sustainable transportation. By examining when, who, and where riders use Bluebikes, the analysis uncovers peak demand patterns, sustainability behaviors, and station-level performance to inform data-driven urban mobility planning.

Using nearly 100,000 real rider trips, this project delivers actionable insights that can help Boston optimize bike availability, improve station placement, and accelerate adoption of green commuting.

---

## Big Idea
**By optimizing Bluebikes demand, Boston can reduce urban congestion by ~15% while significantly boosting sustainable transportation adoption.**

---

## Key Questions
- When does the Bluebikes network experience peak demand pressure?
- Who drives sustainable adoption — members or casual riders?
- Which stations and routes are most critical to network performance?
- How can data guide smarter station expansion and capacity planning?

---

## Dataset Overview
- **Records:** 98,382 Bluebikes trips  
- **Geography:** Greater Boston Area  
- **Time Period:** 2023–2024  
- **Features:** Trip start & end times, duration, station locations  
- **User Types:** Members vs. casual riders  
- **Source:** Bluebikes Open Data Portal  

---

## Analysis Structure

### Peak Demand Analysis (When)
- Strong weekday dominance confirms commuter-driven usage
- Clear dual peak pattern:
  - Morning rush: **7–9 AM**
  - Evening rush: **5–7 PM** (higher than morning)
- Rush hours account for **44.1% of all trips**
- Peak usage hour: **5 PM**
- Most popular route: **Central Sq → MIT Pacific St**

**Recommendations**
- Expand bike capacity by ~40% during rush hours
- Prioritize high-demand routes for redistribution
- Introduce off-peak pricing to shift discretionary trips

---

### Sustainability Behavior Analysis (Who)
- **Members drive sustainability**
  - 85.8% of trips made by members
  - Strong rush-hour commuting behavior
- Casual riders show flatter, leisure-focused usage
- Member trips are **1.3× shorter**, indicating more efficient ride patterns

**Recommendations**
- Convert casual riders to members through targeted incentives
- Promote corporate and commuter membership programs
- Leverage strong member base to scale green mobility adoption

---

### Station & Network Optimization (Where)
- Top 10 stations handle **14.5% of total system activity**
- Busiest station: **MIT at Mass Ave / Amherst St**
- High-demand stations cluster near universities and transit hubs
- **82.2% of stations fall in low-activity zones**, indicating underutilized capacity

**Recommendations**
- Prioritize infrastructure investment at high-activity hubs
- Strengthen connectivity along busiest routes
- Expand into underused areas to balance the network

---

## Key Insights
- Rush hours (7–9 AM, 5–7 PM) account for **44% of all trips**
- **85.8%** of rides are made by members, confirming strong sustainable commuting behavior
- Demand is highly concentrated across a small set of stations
- Strategic capacity planning can significantly reduce congestion

---

## Expected Impact
- **~15% reduction in urban congestion**
- **2× increase in sustainable transportation usage**
- More balanced and efficient bike-sharing network across Boston

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Jupyter Notebook
- Data visualization and storytelling techniques
- Open urban mobility datasets

## Data Source
The analysis uses publicly available Bluebikes trip-level data provided through the Bluebikes Open Data Portal.

- **Source:** Bluebikes Open Data Portal  
- **Geography:** Greater Boston Area  
- **Time Period:** 2023–2024  
- **Records:** 98,382 individual bike trips  
- **Granularity:** Trip-level data  

### Key Features
- Trip start and end timestamps  
- Trip duration  
- Start and end station locations  
- User type (Member vs. Casual rider)  

The dataset is anonymized and does not contain personally identifiable information. It is commonly used for urban mobility, transportation planning, and sustainability research.


---

## Repository Structure
bluebikes-urban-mobility-analysis/
├── notebooks/ # Analysis and storytelling notebook
├── reports/ # Hackathon presentation
└── README.md

## Why This Project Matters
This project demonstrates how real-world mobility data can be transformed into clear, policy-relevant insights that improve urban infrastructure, reduce congestion, and promote sustainable transportation at scale.
