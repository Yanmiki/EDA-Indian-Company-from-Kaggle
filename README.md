# Flight Price Analysis: Indian Domestic Air Travel

📊 **Exploratory Data Analysis (EDA)** of flight booking data from Indian airlines.  
This project explores patterns in flight prices, routes, timing, and airline preferences across major Indian cities.

---

## 📌 Project Overview

Flight booking data was collected from a well-known travel website in a structured format. The dataset contains information about **domestic flights in India**, including:

- ✈️ **Airlines**: Vistara, Air India, Indigo, SpiceJet, GO_FIRST, AirAsia
- 🛫 **Departure and arrival cities**: Delhi, Mumbai, Bangalore, Chennai, Kolkata, Hyderabad
- ⏰ **Departure and arrival times**: Early morning, Morning, Evening, Night, Late Night
- 📅 **Days left before departure**
- 💰 **Ticket price** (in INR)
- 🪑 **Class**: Economy and Business
- 🕐 **Flight duration**

The goal is to understand **what factors influence flight prices** and to uncover **travel patterns** in the Indian domestic market.

---

## 🔍 Key Questions Explored

Q.1. What are the airlines in the dataset, accompanied by their frequencies?

Q.2. Show Bar Graphs representing the Departure Time & Arrival Time.

Q.3. Show Bar Graphs representing the Source City & Destination City.

Q.4. Does price varies with airlines?

Q.5. Does ticket price change based on the departure time and arrival time?

Q.6. How the price changes with change in Source and Destination?

Q.7. How is the price affected when tickets are bought in just 1 or 2 days before departure?

Q.8. How does the ticket price vary between Economy and Business class?

Q.9. What will be the Average Price of Vistara airline for a flight from Delhi to Hyderabad in Business Class?

---

## 📊 Visualizations

Included in the notebook:
- Bar plots: most popular source/destination cities
- Line plots: price trends over days left
- Box plots: price distribution by airline and class
- Heatmaps: correlation and Phik matrix
- Pivot tables: detailed price summaries

All visualizations are created using:
- `seaborn` and `matplotlib` for plotting
- `pandas` and `phik` for data analysis

---

## 🧰 Technologies Used

- **Python** 🐍
- **Jupyter Notebook** 📓
- **pandas** – data manipulation
- **numpy** – numerical operations
- **seaborn**, **matplotlib** – data visualization
- **phik** – correlation analysis for categorical variables
