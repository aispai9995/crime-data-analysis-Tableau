# 🚨 Crime Data Analysis & Dashboard | Tableau  
This project explores **crime patterns in Chicago (2013–2023)** using Tableau visualizations, Level of Detail (LOD) expressions, calculated fields, and a variety of chart types. The goal was to uncover **crime trends, policing gaps, and socio-economic drivers of crime**, and to provide **actionable recommendations** for law enforcement and policymakers.  

---

## 📊 Project Overview  
- **Objective:** Analyze Chicago crime data to identify high-risk crime types, arrest gaps, and socio-economic influences such as income, unemployment, and education.  
- **Scope:** Data from **2013–2023** was used (2012 and earlier excluded due to missing data; 2024 excluded as partial year).  
- **Techniques:**  
  - **LODs (Level of Detail Expressions):** To calculate crimes/arrests per capita normalized by population.  
  - **Calculated Fields:** To derive KPIs such as arrest percentage goals vs. actuals.  
  - **Multiple Graph Types:**  
    - **Bar Charts:** For top crime categories & arrest trends.  
    - **Scatterplots:** To show correlation between crime rates and unemployment.  
    - **Bivariate Choropleth Map:** For spatial analysis of crime vs. education.  
    - **Line Charts:** To illustrate crime and arrest trends across time.  

---

## 📌 Key Visualizations & Insights  

### 📍 Viz 1: Top 10 Crime Types (Per Capita vs. Arrests Per Capita)  
- **Chart Used:** Bar Chart (normalized with LODs).  
- Theft, Battery, and Criminal Damage account for **~50% of all crimes per capita**.  
- Arrests disproportionately focused on **narcotics**, leading to long-term reduction in narcotic crimes.  
- **Recommendation:** Refocus arrests on Theft, Battery, and Criminal Damage to reduce the most common crime categories.

<img width="1240" height="996" alt="image" src="https://github.com/user-attachments/assets/9f73fb9d-fd17-4214-8418-779d75693904" />
---

### 📍 Viz 2: Actual Arrest % vs. Target Arrest %  
- **Chart Used:** Bar Chart + Calculated Fields.  
- Police consistently achieve arrest targets for **Narcotics, Gambling, Prostitution, Liquor Law Violations, Public Indecency**.  
- Arrest goals for **Theft, Battery, and Criminal Damage** are unmet, even though they dominate crime volume.  
- **Recommendation:** Prioritize enforcement on high-volume crimes and serious offenses like Homicide and Assault.  

<img width="1452" height="956" alt="image" src="https://github.com/user-attachments/assets/5c725196-f0d4-4be7-bd12-f91c9aba35d6" />

---

### 📍 Viz 3: Crime vs. Unemployment Scatterplot  
- **Chart Used:** Scatterplot (X-axis unemployment %, Y-axis crime rate).  
- Communities with **high unemployment show higher crime rates** (e.g., Fuller Park → Crime Rate 33%, Unemployment 31%).  
- **Recommendation:** Police and city leaders should partner on **employment initiatives + community policing** to stabilize high-risk neighborhoods.  

<img width="989" height="765" alt="image" src="https://github.com/user-attachments/assets/f32013d2-eeba-455c-8722-327d1dbcb4ac" />

---

### 📍 Viz 4: Bivariate Choropleth (Crime vs. Higher Education)  
- **Chart Used:** Bivariate Choropleth Map (3x3 diverging color grid).  
- Communities like **Fuller Park & Englewood** → **high crime + low education**, compounded by low income and high youth population.  
- **Recommendation:**  
  - Law enforcement → increased presence in hotspots.  
  - Community leaders → education, mentoring, youth programs.  
  - NGOs → scholarships, internet access, and summer programs.  

<img width="1485" height="1069" alt="image" src="https://github.com/user-attachments/assets/42c13dee-2317-42df-8fe8-b0859018a36d" />

---

## 🚀 Overall Recommendations  
- Realign arrest priorities toward **high-frequency crimes** (Theft, Battery, Criminal Damage).  
- Expand enforcement on **serious crimes against people** (Assault, Homicide, Human Trafficking).  
- Pair policing with **community-based interventions** targeting unemployment, education, and youth engagement.  
- Build **public-private partnerships** to fund education, job programs, and mental health services.  

---

## 🛠️ What I Learned  
✔️ Applied **LODs** to calculate per-capita crime metrics and normalize across populations.  
✔️ Built **calculated fields** for KPIs like arrest % vs. target.  
✔️ Used **diverse chart types** (bar, scatterplot, choropleth, line chart) to tell a multi-faceted story.  
✔️ Improved skills in **custom mapping, geocoding, and advanced Tableau design**.  
✔️ Learned how to transform insights into **policy-relevant strategies**.  

---
#### If you like to know more about the project, reach me @ aiswaryarpai@gmail.com
