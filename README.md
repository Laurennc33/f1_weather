# Formula One Tire and Weather Strategy Analysis


## **Project Overview**
This project aims to analyze the impact of tyre strategy and weather conditions on driver performance and race outcomes in Formula 1 races. By leveraging telemetry data, laps data, and weather data, we seek to uncover insights that can inform race strategies.

---

## **Table of Contents**
- Central Motivation
- Key Questions
- Data Processing Overview
- Getting Started
- Installation
- Data Sources
- Contribution
  
---

## **Central Motivation**
Understanding how tyre strategy and changing weather conditions influence race outcomes is critical for teams aiming to optimize performance. This project will analyze these factors to provide actionable insights into race strategy.

---

## **Key Questions**
1. How does tyre strategy impact driver performance and race outcomes under varying weather conditions?
2. How do changing weather conditions influence pit stop timing and tyre choices throughout the race?

---

## **Data Processing Overview**

1. **Data Ingestion**: Collect data from race sessions, including event logs, telemetry, and weather data.

2. **Preprocessing**:  
   - **Laps Data**: Fill missing pit stop times, remove deleted or inaccurate laps, and map track statuses to meaningful labels.
   - **Telemetry Data**: Correct data types, remove outliers in speed, RPM, and gears, and handle interpolated data carefully.
   - **Weather Data**: Align weather timestamps with lap data, filter out unrealistic wind speed values, and group rainfall events.

3. **Exploratory Data Analysis (EDA)**: Visualize strategies, weather patterns, and their impact on race outcomes.

4. **Modeling/Analysis**: Apply statistical methods to assess relationships between tyres, weather, and strategy.

5. **Reporting**: Summarize findings in a report, providing answers to the key questions with visualizations and insights.

---

## **Getting Started**
To run this project locally, follow the instructions below.

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/f1_weather.git
   cd f1_weather
   ```

2. Install required packages:
   ```bash
   pip install fastf1
   ```

---

## **Data Sources**
- FastF1 Python library for data access

---

## Contribution
This is a final project for our groups foundatinos of data science class. The members in the group are Lauren Cummings, Riyana Roy, Satvik Repaka, and Justin Huang.

---

This project is not sponsored or affiliated with Formula 1, Formula One Management, or any of its associated teams or organizations. The data used in this project is collected from publicly available sources and analyzed for educational and informational purposes only.

