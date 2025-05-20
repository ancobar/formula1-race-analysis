# 🏎️ Formula 1 Race Analysis
**Group Assignment for Python I – Data Exploration and Visualization with Formula 1 Dataset**

This project explores historical Formula 1 data to uncover trends, performance indicators, and race statistics through structured analysis and visualizations.

## 👥 Team Members

- Ana Cortés  
- Margarida Pereira  
- Enrico Miguel Tajanlangit  
- Kevin Tochkov  
- Vibhushan Balaji Neethi Mohan


## 📁 Dataset

The dataset `F1_Data.csv` includes detailed records of F1 races, drivers, constructors, circuits, and performance metrics across multiple seasons.

### Key features:
- Driver info: `driver`, `driver_dob`, `driver_nationality`
- Race data: `grid_starting_position`, `final_position`, `points`, `laps`, `fastest_lap`, `total_race_time_ms`
- Circuit data: `circuit_name`, `circuit_country`, `altitude`, `lat`, `lng`
- Constructor: `constructor_name`, `constructor_nationality`
- Event info: `race_name`, `year`, `race_date`, `status`, etc.


## 🎯 Project Objectives

- Clean and explore F1 race data
- Perform feature-based analysis (drivers, circuits, seasons, performance)
- Use visualizations to support findings
- Focus the final presentation on one driver, constructor, or circuit


## 📈 Key Analyses Performed

- Total points by driver and constructor
- Relationship between grid position and final results
- Fastest lap trends by year
- Driver performance over career
- Circuit-level average speeds and outcomes
- DNF (Did Not Finish) patterns by track or constructor


## 📊 Visualizations

Includes:
- Bar plots of total points and wins
- Line charts showing performance trends over time
- Scatter plots (e.g., grid position vs final result)
- Heatmaps and circuit-based visual summaries


## 🧠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebooks


## 📂 Project Structure
- README.md >>> Project documentation and overview (this file)
- F1_Data.csv >>> Dataset used for the analysis (driver, constructor, circuit, and race performance)
- F1_Analysis_Notebook.ipynb >>> Jupyter Notebook containing full Formula 1 data analysis and visualizations
