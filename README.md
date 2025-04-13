#  Analyzing Crime Data in Los Angeles (2020–Present)

This repository contains a data science project focused on analyzing crime patterns in **Los Angeles** using publicly available data from 2020 onwards. The goal of the project is to identify key trends, crime hotspots, demographic patterns, seasonal influences, and more — all through meaningful data visualization and statistical analysis.

---

##  Dataset Source

The dataset used in this project was obtained from the official **Los Angeles Open Data Portal**:  
🔗 [LA Crime Data (2020–Present)](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8)

- **Size:** 2.5M+ rows (updated regularly)  
- **Time Period Covered:** 2020 to Present  
- **Features:** Date, Crime Code, Area, Victim/Suspect Info, Weapon Used, Status, and more.

---

##  Objectives

1. Analyze monthly and yearly crime trends to identify patterns over time  
2. Determine the frequency and proportion of various crime types  
3. Identify areas with high concentrations of criminal activity  
4. Analyze the age, gender, and race of victims and suspects  
5. Examine how crime incidents vary by day of the week and time of day  
6. Investigate the types of weapons used in crimes and their prevalence  
7. Identify seasonal variations in crime occurrences  
8. Assess the frequency of repeat offenders  
9. Evaluate the influence of COVID-19 on crime trends  
10. Analyze the proportion of crimes solved or cleared by law enforcement  

---

##  Technologies Used

- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Jupyter Notebook**

---

##  Data Preprocessing

- Converted `DATE OCC` to extract Year, Month, Day, and Weekday  
- Standardized `TIME OCC` into readable time periods  
- Dropped duplicates and missing values  
- Created new features (season, hour of crime, etc.) for deeper analysis  
- Mapped codes to human-readable formats (e.g., crime categories, weapon types)

---

##  Visualizations & Key Insights

- **Line Charts** for overall crime trends over time  
- **Bar & Pie Charts** showing top crime types, solved cases, and weapon usage  
- **Heatmaps** for area-wise crime hotspots and crime vs. weapon combinations  
- **Histograms** for age distributions of victims and suspects  
- **Time-Based Plots** to analyze variation by day, hour, and season  
- **COVID Timeline Analysis** to examine changes before, during, and after lockdowns  

---

##  Key Takeaways

- *Vehicle theft** was consistently the most reported crime  
-  Crimes involving **firearms** were most common among violent offenses  
-  **Crime peaks during winter**, especially property crimes  
-  **Cybercrime and domestic violence increased** during COVID lockdown  
-  Only about **30% of crimes are solved**, with violent crimes having higher clearance rates  

---

##  Project Report

A complete report with in-depth analysis, visuals, and conclusions is included in the repository as a **PDF file**.

---

##  Acknowledgements

Thanks to **Lovely Professional University** and our faculty mentors for their guidance and support during this project. This work was done as part of the **Data Science Minor Project (Jan–April 2025)**.

---

## 📎 License

This project is for academic and educational purposes only. Feel free to fork or use it for learning or non-commercial use.
