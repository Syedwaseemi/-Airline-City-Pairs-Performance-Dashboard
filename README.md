# -Airline-City-Pairs-Performance-Dashboard
This project focuses on analyzing Australian domestic airline city-pair traffic data using Power BI. The dataset includes key metrics such as passengers, flights, available seats, distance, and load factors across multiple routes and time periods. The dashboard provides interactive visualizations to track airline performance,.

.
.![Uploading Screenshot 2025-08-23 150431.png…]()

.
.
.
.
.
.
📌 Project Overview

The Airline City Pairs Performance Dashboard analyzes Australian domestic airline city-pair traffic data using Power BI.
It transforms raw CSV data into interactive and professional insights covering passengers, flights, seats, distance, and load factors across multiple routes and time periods.

🎯 Objectives

Convert raw airline traffic data into a professional Power BI dashboard.

Create KPIs: Passengers, Flights, Available Seats, Distance, and Load Factor.

Identify top-performing routes and cities.

Provide trend analysis with slicers for dynamic filtering.

Showcase dashboard design skills for professional use.

📂 Dataset Information

Source: Australian Domestic Airline City Pairs Data (CSV files – monthly, 2019).

Key Columns:

Month → Reporting period

City1 → Origin city

City2 → Destination city

Passengers → Number of passengers

Flights → Number of flights operated

Seats → Available seats

Distance → Distance between cities

Load_Factor → Efficiency ratio (Passengers ÷ Seats × 100)

⚙️ Steps to Build Dashboard

Import Data

Open Power BI → Get Data → Text/CSV → Load all monthly CSVs.

Data Transformation (Power Query)

Combine files into one table.

Ensure correct data types (Date for Month, Number for metrics).

Remove nulls/duplicates.

Create DAX Measures

Total Passengers = SUM(Passengers)

Total Flights = SUM(Flights)

Total Seats = SUM(Seats)

Avg Load Factor = AVERAGE(Load_Factor)

Total Distance = SUM(Distance)

Design Visuals

KPI Cards (Passengers, Flights, Seats, Distance, Load Factor).

Line Chart (Passengers Trend by Month).

Bar Chart (Top 10 Routes by Passengers).

Table (Detailed route metrics).

Map (Passenger traffic by City1/City2).

Slicers (Month, City1, City2).

Dashboard Layout

Title: ✈️ Airline City Pairs Performance Dashboard

Top section: KPI Cards

Middle: Trend line chart + Top routes bar chart

Bottom: Table + Map

Side panel: Slicers

📊 Dashboard Preview

(Add a screenshot once your Power BI dashboard is ready.)

🚀 How to Use

Open Airline_Dashboard.pbix in Power BI Desktop.

Use slicers to filter by city or time.

Export dashboard to Power BI Service or PDF for sharing.

📈 Skills Highlighted

Data Cleaning & Transformation (Power Query)

DAX Calculations

Professional Dashboard Design

Business Insights Presentation

👨‍💻 Author

Syed Waseem

🎓 Final-year Software Engineering Student (PES Institute of Technology & Management, Shimoga)

💻 Full-Stack Developer | Data Analyst

🌐 GitHub
 | LinkedIn
 
🖋️ Watermark

🔒 This project is created by Syed Waseem. Unauthorized use or plagiarism without credit is not allowed.
