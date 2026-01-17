# ✈️ Flight Price Analysis & Visualization using Python

A data analysis and visualization project that explores airline flight pricing patterns using real-world flight data. This project focuses on **exploratory data analysis (EDA)** and generating meaningful insights through **statistical analysis and visualizations**.

---

## 📌 Project Overview

This project analyzes a comprehensive airline flights dataset to understand how different factors such as **flight duration, days left before departure, airline, class, stops, source city, and destination city** affect flight prices.

The goal is to transform raw flight data into **clear visual insights** that help explain pricing trends and airline behavior.

---

## 🎯 Objectives

* Perform exploratory data analysis (EDA) on flight data
* Identify key relationships between price and other features
* Visualize trends using graphs and plots
* Draw meaningful conclusions from data

---

## 🛠️ Technologies & Tools Used

### Programming & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

### Environment

* **Jupyter Notebook / Google Colab**
* **VS Code** (optional)

---

## 📂 Project Structure

```
Flight_Price_Analysis/
│
├── flight_dataset.py
├── airlines_flights_data.csv
└── README.md
```

---

## 📊 Dataset Description

The dataset contains **300,000+ flight records** with the following key attributes:

* **Airline** – Name of the airline
* **Source City** – City of departure
* **Destination City** – City of arrival
* **Departure Time / Arrival Time** – Time categories
* **Stops** – Number of stops (0, 1, 2+)
* **Class** – Economy or Business
* **Duration** – Flight duration
* **Days Left** – Days remaining before departure
* **Price** – Flight ticket price (target variable)

Dataset file: `airlines_flights_data.csv`

---

## 🔄 Data Analysis Workflow

1. Load and inspect dataset
2. Understand data types and distributions
3. Analyze categorical and numerical features
4. Identify relationships suitable for visualization
5. Generate visualizations
6. Interpret results and insights

---

## 📈 Visualizations Created

### 1️⃣ Price vs Duration (Scatter Plot)

* Shows relationship between flight duration and ticket price
* Helps identify correlation and pricing spread

### 2️⃣ Price vs Days Left (Scatter Plot)

* Analyzes impact of booking time on flight price
* Confirms higher prices for last-minute bookings

### 3️⃣ Price Distribution by Airline (Box Plot)

* Compares pricing strategies of different airlines
* Highlights premium airlines like Vistara

### 4️⃣ Price Distribution by Class (Box Plot)

* Shows significant price difference between Economy and Business class

### 5️⃣ Price Distribution by Stops (Box Plot)

* Explores how number of stops affects pricing

### 6️⃣ Flight Frequency by Source City (Count Plot)

* Identifies major flight hubs

### 7️⃣ Flight Frequency by Destination City (Count Plot)

* Shows most common destination cities

---

## 🔁 Flowchart (Text Representation)

```
[ Load Dataset ]
        ↓
[ Data Exploration ]
        ↓
[ Feature Analysis ]
        ↓
[ Visualization Selection ]
        ↓
[ Plot Generation ]
        ↓
[ Insight Extraction ]
```

---

## ▶️ How to Run the Project

```bash
# Clone the repository
git clone <repo-url>

# Navigate to project directory
cd Flight_Price_Analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run the script
python flight_dataset.py
```

---

## 🧠 Key Insights

* Flight prices generally increase with duration
* Prices rise sharply as departure date approaches
* Business class flights are significantly more expensive
* Vistara shows consistently higher median prices
* Delhi and Mumbai are the busiest flight hubs

---

## 🚀 Future Enhancements

* Predictive modeling for flight prices
* Feature importance analysis
* Interactive dashboards (Streamlit / Power BI)
* Route-based pricing analysis

---

## 👨‍💻 Author

**Anant Goel**
B.Tech – Data Science
Aspiring Data Scientist | Python & Data Analytics Enthusiast

---

## ⭐ Support

If you found this project helpful, please **star ⭐ the repository** and share feedback!
