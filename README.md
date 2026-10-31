✈️ Airline Flight Analysis

An exploratory data analysis project using Python and Pandas to uncover insights on ticket pricing, delays, cancellations and passenger traffic across major Indian airlines.

Show Image Show Image Show Image Show Image

📌 Project Overview

This project analyses a sample dataset of 20 domestic flights operated by IndiGo, Air India, Vistara and SpiceJet in January 2026. It demonstrates an end-to-end analysis workflow: building the dataset, exploring it, calculating key business metrics and presenting findings through charts.

🎯 Objective: Understand how airlines compare on price, punctuality and reliability, and how distance and date relate to fares and passenger volume.

🗂️ Dataset
Column	Description
Flight_ID	Unique flight identifier
Airline	IndiGo, Air India, Vistara, SpiceJet
Flight_Number	Airline flight code
Source / Destination	Departure and arrival cities
Flight_Date	Date of the flight (5–24 Jan 2026)
Ticket_Price	Fare in INR (₹)
Distance	Distance travelled (km)
Duration	Flight time (hours)
Passengers	Number of passengers on board
Delay_Minutes	Delay in minutes
Flight_Status	Completed / Delayed / Cancelled
Cancellation_Status	Cancelled / Not Cancelled
🛠️ Tools & Skills
🐍 Python – core programming
🐼 Pandas – data loading, aggregation, filtering, group-by analysis
📊 Matplotlib – bar, line and scatter charts
📓 Jupyter Notebook – documented, reproducible analysis
💾 CSV handling – exporting and re-importing data
🔍 Analysis Performed
📥 Created the dataset and saved/loaded it as a CSV file
🧐 Explored structure using info(), shape, describe(), head() and tail()
📈 Calculated key metrics (average, maximum and minimum price, average duration)
🧮 Grouped data by airline for flight count, average fare and average delay
🚦 Filtered flights with delays above 30 minutes and cancelled flights
📉 Visualised trends with four charts
📊 Key Findings
📌 Metric	Result
Total flights analysed	20
Total passengers	3,120 (avg. 156 per flight)
Average ticket price	₹6,260
Highest / lowest fare	₹8,100 / ₹4,300
Average flight duration	2.18 hours
Average delay	17.25 minutes
Flights completed on time	70% (14 of 20)
Flights delayed	25% (5 of 20)
Flights cancelled	5% (1 of 20)
💡 Insights
💰 Air India is the most expensive (avg ₹7,640), while IndiGo is the most affordable (avg ₹5,117).
⏱️ IndiGo is the most punctual (avg delay 5 min); Air India has the longest average delay (35 min).
🛫 IndiGo operates the most flights in the dataset (6), followed by Air India and Vistara (5 each) and SpiceJet (4).
⚠️ 4 flights were delayed by more than 30 minutes, 3 of them operated by Air India.
📏 Ticket price generally rises with distance, shown by the scatter plot.
🏆 Airline Comparison
Airline	Flights	Avg. Ticket Price	Avg. Delay
✈️ Air India	5	₹7,640	35 min
✈️ SpiceJet	4	₹6,575	25 min
✈️ Vistara	5	₹6,000	8 min
✈️ IndiGo	6	₹5,117	5 min
📉 Visualisations
📊 Number of flights per airline (bar chart)
💵 Average ticket price by airline (bar chart)
📅 Total passengers by flight date (line chart)
🔵 Distance vs. ticket price (scatter plot)
🚀 How to Run
bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git

# 2. Install dependencies
pip install pandas matplotlib jupyter

# 3. Launch the notebook
jupyter notebook airline_flight_analysis_project.ipynb
⚠️ Limitations

This is a small, hand-built sample dataset (20 rows). The findings demonstrate analytical technique and are not representative of real-world airline performance.

🔮 Future Improvements
Use a larger real-world dataset
Add route-level and month-wise analysis
Build an interactive dashboard (Power BI / Streamlit)
Apply a regression model to predict ticket prices
