# aviation-data-analysis
Flights Delay And Cancellation Analysis Using Python ,and Power BI
✈️ Aviation Data Analysis – Flight Delay & Airport Operations

This project analyzes flight operations data to understand flight delays, airline performance, airport operations, and cancellation patterns using Python,and Power BI.

The project focuses on transforming raw flight data into meaningful insights that can support better operational analysis and decision-making in the aviation domain.

---

📌 Project Overview

Airline operations generate large volumes of data related to flights, delays, cancellations, airports, routes, and airline performance.

This project analyzes approximately 3 million flight records to identify:

- Airline-wise flight volume and delay patterns
- Airport-wise arrival and departure delays
- Frequently used airports and routes
- Flight cancellation patterns
- Operational performance indicators
- Key insights through an interactive Power BI dashboard

The overall workflow includes data cleaning, exploratory data analysis, SQL analysis, and dashboard development.

---

🎯 Project Objective

The main objectives of this project are to:

- Analyze flight operational data
- Identify airlines with higher flight volumes
- Compare average delays across airlines
- Identify airports with higher arrival and departure delays
- Analyze frequently used airports and routes
- Understand flight cancellation patterns
- Build an interactive dashboard for better visualization
- Generate meaningful insights from large-scale flight data

---

📊 Dataset Information

Dataset: Flights Sample 3M
Records: Approximately 3 Million
Columns: 32
Domain: Aviation / Airline Operations
Source: Kaggle
Format: CSV

The dataset contains information related to flight operations, including airline details, airports, flight timings, delays, cancellations, routes, and other operational attributes.

Due to GitHub file-size limitations, the complete dataset is hosted externally.

Full Dataset

Full Dataset (~650 MB):
https://mega.nz/file/gUdllLoB#UGcQB_WHEBNMezSlTYF1Y2aE1T3lztN0tpSFHcEo4Ak

Power BI Dashboard

Power BI Dashboard (.pbix):
https://mega.nz/file/4INCARDS#fNRVKw5IhkVKu6D2Np45bv0mWGqmhjJdQnga06xFMiY

A smaller sample dataset is included in the repository for demonstration and testing purposes.

---

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- SQL
- Power BI
- CSV

---

🔄 Project Workflow

Raw Flight Data
       ↓
Data Understanding
       ↓
Data Cleaning & Preprocessing
       ↓
Exploratory Data Analysis
       ↓
SQL Analysis
       ↓
Power BI Dashboard
       ↓
Insights & Business Interpretation

---

🧹 Data Cleaning & Preprocessing

The raw dataset was checked and prepared before performing analysis.

The following activities were performed:

- Data type checking
- Column name formatting
- Missing value analysis
- Appropriate missing-value handling
- Categorical value checking
- Duplicate record checking
- Numerical data validation
- Distribution analysis
- Outlier analysis using visualizations
- Preparation of clean data for SQL and Power BI analysis

---

📈 Exploratory Data Analysis

The project includes analysis of different aspects of flight operations.

✈️ Airline Analysis

Analyzed:

- Total flights by airline
- Average delay by airline
- Airline-wise operational volume
- Comparison of airline performance

🛫 Airport Analysis

Analyzed:

- Total flights by airport
- Average arrival delay
- Average departure delay
- Airports with higher delay values
- Frequently used airports

🛣️ Route Analysis

Analyzed:

- Frequently used flight routes
- Route-level flight activity
- Route-level delay patterns

⏱️ Delay Analysis

Analyzed:

- Average arrival delays
- Average departure delays
- Airline-wise delay performance
- Airport-wise delay performance

❌ Cancellation Analysis

Analyzed:

- Cancelled flights
- Cancellation patterns
- Cancellation codes
- Airline-wise cancellations

---

🗄️ SQL Analysis

SQL was used to perform analytical queries on the cleaned flight data.

Key SQL analysis includes:

- Total flights by airline
- Average departure delay
- Average arrival delay
- Cancelled flights by airline
- Busiest airports
- Frequently used routes
- Airport-wise delay analysis
- Delay category analysis
- Cancellation code analysis

---

📊 Power BI Dashboard

An interactive Power BI dashboard was developed to provide a visual overview of flight operations.

Dashboard KPIs

- Total Flights: 2.92086M
- Average Arrival Delay: 4.26
- Average Airport Delay: 10.10

Airline Analysis

The dashboard compares:

- Total flights by airline
- Average delay by airline

Southwest Airlines Co. has the highest displayed flight volume with approximately 557.01K flights.

Among the displayed airlines, Allegiant Air has the highest average delay at 13.28.

Airport Analysis

The dashboard shows the top airports based on:

- Average arrival delay
- Average departure delay
- Total flight volume

PPG has the highest displayed average arrival delay among the top airports at 56.45.

For total flight volume, ATL is the highest among the displayed airports with approximately 151K flights, followed by DFW (126K) and ORD (119K).

Interactive Filters

The dashboard includes interactive slicers such as:

- Airline
- Origin Airport

These filters allow users to explore the data based on selected airlines and airports.

---

🔍 Key Insights

1. The dashboard represents approximately 2.92 million flights.
2. The displayed average arrival delay is 4.26.
3. Southwest Airlines Co. has the highest displayed flight volume at 557.01K.
4. Delta Air Lines, American Airlines, and SkyWest Airlines also have high flight volumes.
5. Allegiant Air has the highest displayed average airline delay at 13.28.
6. JetBlue Airways and Frontier Airlines also show relatively high displayed average delays.
7. The displayed average airport delay is 10.10.
8. PPG has the highest displayed average arrival delay among the top airports at 56.45.
9. ATL has the highest displayed total flight volume among the top airports at approximately 151K.
10. DFW and ORD follow with approximately 126K and 119K flights respectively.

---

💼 Business Value

The analysis can help understand airline and airport operational performance by providing visibility into:

- Flight volume
- Delay patterns
- Airport performance
- Airline performance
- Cancellation activity
- Frequently used routes

The dashboard provides an interactive way to explore operational data and identify areas that may require further investigation.

---

📁 Project Files

aviation-data-analysis/
│
├── flights.ipynb
├── sample_flight_data.csv
└── README.md

---

🚀 How to Run the Project

1. Clone the Repository

git clone https://github.com/Shreyas1924/aviation-data-analysis.git

2. Open the Jupyter Notebook

Open:

flights.ipynb

using Jupyter Notebook, JupyterLab, or VS Code.

3. Explore the Power BI Dashboard

Download the ".pbix" file using the Power BI Dashboard link provided above and open it in Microsoft Power BI Desktop.

---

👥 Project Team

Project Developed By:

- K.Teja Sri
- M.Nikitha

Domain: Aviation / Airline Operations
Project Area: Data Analytics

---

📌 Conclusion

This project demonstrates how large-scale flight data can be transformed into meaningful analytical insights using Python, SQL, and Power BI.

The combination of data cleaning, exploratory analysis, and interactive visualization provides a structured approach to understanding flight delays, airline performance, airport operations, routes, and cancellations.

The project also demonstrates an end-to-end Data Analytics workflow, from raw data preparation to business-oriented dashboard reporting.
