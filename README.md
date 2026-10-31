# ✈️ Airline Flight Analysis (Python, Pandas & Matplotlib)

![Python](https://img.shields.io/badge/Python-Programming-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)
![Project](https://img.shields.io/badge/Project-EDA-green)

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) using Python, Pandas, and Matplotlib.

The objective is to analyze domestic airline flight data and identify insights related to ticket prices, flight delays, cancellations, passenger traffic, and airline performance.

The analysis covers 20 sample domestic flights operated by IndiGo, Air India, Vistara, and SpiceJet during January 2026.

## 🎯 Project Objectives

- Compare ticket prices across different airlines.
- Analyze flight delays and cancellations.
- Understand passenger traffic across flight dates.
- Identify the most affordable and expensive airlines.
- Explore the relationship between flight distance and ticket price.
- Generate meaningful business insights using data visualization.

## 🗂️ Dataset Description

The dataset contains 20 flight records with the following columns:

| Column Name | Description |
|---|---|
| Flight_ID | Unique flight identifier |
| Airline | Airline name |
| Flight_Number | Airline flight code |
| Source | Departure city |
| Destination | Arrival city |
| Flight_Date | Flight date |
| Ticket_Price | Ticket fare in INR |
| Distance | Distance travelled in KM |
| Duration | Flight duration in hours |
| Passengers | Number of passengers |
| Delay_Minutes | Flight delay in minutes |
| Flight_Status | Completed / Delayed / Cancelled |
| Cancellation_Status | Cancelled / Not Cancelled |

## 🛠️ Tools & Technologies

- **Python:** Core programming language.
- **Pandas:** Data cleaning, filtering, grouping, and aggregation.
- **Matplotlib:** Data visualization using charts.
- **Jupyter Notebook:** Interactive analysis and documentation.
- **CSV:** Dataset storage and handling.

## 🔍 Analysis Performed

### 1. Dataset Creation
- Created a sample flight dataset using Pandas.
- Exported the dataset into a CSV file.
- Imported the CSV file into Jupyter Notebook.

### 2. Data Exploration
Used the following functions:

- `head()`
- `tail()`
- `shape`
- `info()`
- `describe()`

### 3. Data Analysis
- Calculated average, maximum, and minimum ticket prices.
- Calculated average flight duration and delay.
- Grouped flights by airline.
- Compared airline-wise average ticket prices.
- Analyzed passenger traffic by flight date.
- Filtered flights with delays above 30 minutes.
- Identified cancelled flights.

### 4. Data Visualization
Created four different charts using Matplotlib.

## 📊 Key Performance Indicators (KPIs)

| Metric | Result |
|---|---:|
| Total Flights Analysed | 20 |
| Total Passengers | 3,120 |
| Average Passengers per Flight | 156 |
| Average Ticket Price | ₹6,260 |
| Highest Ticket Price | ₹8,100 |
| Lowest Ticket Price | ₹4,300 |
| Average Flight Duration | 2.18 Hours |
| Average Flight Delay | 17.25 Minutes |
| On-time Flights | 70% |
| Delayed Flights | 25% |
| Cancelled Flights | 5% |

## 💡 Key Business Insights

### 💰 Ticket Price Analysis
- Air India has the highest average ticket price of ₹7,640.
- IndiGo has the lowest average ticket price of ₹5,117.

**Insight:** IndiGo offers more affordable ticket prices compared with the other airlines in this sample.

### ⏱️ Flight Delay Analysis
- IndiGo has the lowest average delay of 5 minutes.
- Air India has the highest average delay of 35 minutes.

**Insight:** IndiGo performs better in terms of punctuality in this dataset.

### 🛫 Airline-wise Flight Count
- IndiGo operates 6 flights.
- Air India operates 5 flights.
- Vistara operates 5 flights.
- SpiceJet operates 4 flights.

**Insight:** IndiGo has the highest number of flights in the sample dataset.

### ⚠️ Delay Analysis
- 4 flights experienced delays above 30 minutes.
- 3 out of these 4 delayed flights were operated by Air India.

**Insight:** Higher delays in Air India flights indicate an area for further operational investigation.

### 📏 Distance vs. Ticket Price
The scatter plot shows a general positive relationship between flight distance and ticket price.

**Insight:** Longer-distance flights generally have higher ticket prices in this sample.

## 🏆 Airline Performance Comparison

| Airline | Flights | Avg. Ticket Price | Avg. Delay |
|---|---:|---:|---:|
| Air India | 5 | ₹7,640 | 35 min |
| SpiceJet | 4 | ₹6,575 | 25 min |
| Vistara | 5 | ₹6,000 | 8 min |
| IndiGo | 6 | ₹5,117 | 5 min |

## 📉 Data Visualizations

The project includes four visualizations:

1. **Number of Flights per Airline – Bar Chart:** Compares the number of flights operated by each airline.
2. **Average Ticket Price by Airline – Bar Chart:** Identifies the most expensive and affordable airlines.
3. **Total Passengers by Flight Date – Line Chart:** Shows passenger traffic trends over different dates.
4. **Distance vs. Ticket Price – Scatter Plot:** Examines the relationship between flight distance and ticket prices.

## ❓ Business Questions Answered

1. How many flights are available in the dataset?
2. What is the total number of passengers?
3. Which airline has the highest average ticket price?
4. Which airline offers the lowest average ticket price?
5. Which airline has the lowest average flight delay?
6. How many flights were cancelled?
7. How many flights experienced delays above 30 minutes?
8. How does passenger traffic change by flight date?
9. What is the relationship between distance and ticket price?

## 🎯 Skills Demonstrated

- Python Programming
- Pandas Data Manipulation
- Exploratory Data Analysis (EDA)
- Data Aggregation and GroupBy
- Data Filtering and Sorting
- Statistical Analysis
- Matplotlib Visualization
- Business Insights Generation

## 🚀 How to Run This Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Step 2: Install Dependencies

```bash
pip install pandas matplotlib jupyter
```

### Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Open the Notebook

Open `airline_flight_analysis_project.ipynb` and run the notebook cells.

## ⚠️ Limitations

This project uses a small, manually created sample dataset containing only 20 flight records.

The findings are intended for learning and demonstration purposes and do not represent actual airline performance.

## 🔮 Future Improvements

- Use a larger real-world airline dataset.
- Perform route-wise and month-wise analysis.
- Build an interactive dashboard using Power BI or Streamlit.
- Apply regression techniques to predict ticket prices.
- Analyze additional factors affecting flight delays.

## 👩‍💻 Author

**Pranali Talekar**

Aspiring Data Analyst | Python | SQL | Excel | Power BI
