# 🚗 Dynamic Pricing for Urban Parking Lots  

## 📌 Overview  
This project was developed as part of **Summer Analytics 2025**, hosted by the **Consulting & Analytics Club × Pathway**.  
The aim is to build a **real-time dynamic pricing system** for urban parking lots, helping optimize both **revenue for providers** and **convenience for customers**.  

By leveraging **real-time data**, parking prices are adjusted dynamically based on demand, availability, and time of day. This ensures efficient space utilization and reduces traffic congestion caused by drivers searching for parking.  

---

## 🎯 Purpose  
- Solve the issue of **static pricing** in parking systems.  
- Ensure **fair pricing** for customers while maximizing revenue.  
- Reduce **parking search time** and traffic congestion.  
- Demonstrate how **real-time data streaming and analytics** can be applied in urban infrastructure.  

---

## ⚙️ Working of the Project  

1. **Data Ingestion**  
   - Collects real-time/simulated parking lot data (number of available spots, demand, entry/exit logs, timestamps).  
   - Uses **Pathway** for continuous data streaming and updates.  

2. **Data Preprocessing**  
   - Clean and structure raw data using **Pandas** and **NumPy**.  
   - Extract features like **time of day, weekday/weekend, location popularity, and current occupancy rate**.  

3. **Dynamic Pricing Model**  
   - Pricing is adjusted based on demand-supply ratio:  
     - High demand → higher price.  
     - Low demand → discounted price.  
   - Rules-based and machine learning models tested.  

4. **Real-Time Updates**  
   - Pathway streams live data into the pricing engine.  
   - Parking lot prices are updated in real time without delays.  

5. **Visualization**  
   - Interactive dashboards created with **Bokeh**.  
   - Shows:  
     - Current occupancy  
     - Price changes over time  
     - Demand patterns  
     - Revenue projections  

---

## 🛠️ Tech Stack  
- **Python** 🐍 – Core programming language.  
- **Pandas** – Data cleaning and feature engineering.  
- **NumPy** – Mathematical and statistical computations.  
- **Pathway** – Real-time data streaming & event processing.  
- **Bokeh** – Interactive visualizations and dashboards.  

---


## 📊 Methodology  
1. **Data Collection & Simulation** – Parking entry/exit logs generated.  
2. **Exploratory Data Analysis** – Identify demand patterns, peak hours, and utilization.  
3. **Model Development** – Create rules/ML models for pricing.  
4. **Deployment with Pathway** – Ensure real-time dynamic updates.  
5. **Visualization with Bokeh** – Provide stakeholders with interactive dashboards.  

---

## 🚀 Features  
- Real-time data streaming for **instant price updates**.  
- **Demand-responsive pricing** model.  
- Dashboards to **track occupancy, demand, and revenue**.  
- Extensible framework for **integration with IoT-enabled parking systems**.  

---

## ✅ Outcomes  
- Demonstrated how **dynamic pricing increases parking revenue** compared to flat rates.  
- Reduced idle capacity by encouraging **better space utilization**.  
- Built a **scalable framework** for future smart-city applications.  

---

## 📌 Future Scope  
- Integration with **real-world IoT parking sensors**.  
- Adding **predictive ML models** for forecasting demand.  
- Expansion to **ride-sharing and EV charging stations**.  

---

## 👨‍💻 Contributors  
- **Praveen**  
- Guided under **Summer Analytics 2025** program  

---

