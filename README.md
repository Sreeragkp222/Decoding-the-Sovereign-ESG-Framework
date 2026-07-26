# Decoding-the-Sovereign-ESG-Framework
Capstone project analyzing the World Bank Sovereign ESG Data Framework (2015–2023) to evaluate various Environmental, Social and Governance indicators using Python, Pandas, Matplotlib, Seaborn, and Plotly.
# 🌍 Decoding the Sovereign ESG Framework: Global Sustainability & Policy Analysis

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![World Bank Data](https://img.shields.io/badge/Data-World%20Bank%20ESG-0072C6?style=for-the-badge)

---

## 🎯 Project Aim & Objectives

The primary aim of this Capstone Project is to **analyze the various Environmental, Social and Governance indicators of Global economies and evaluating their perfomance over the years** using the **World Bank’s Sovereign ESG Data Framework**. 

By analyzing multi-year sovereign indicators (2015–2023), this project seeks to evaluate various Geographic regions/ Economies on the basis of several factors including **Emission & Pollution, Energy use & Security Climate risk & resilience, Food security, National capital endowment, Access to services, Demography, Education & Skills, Employment, Health & Nutrition, Poverty & Inequality, Economic environment, Gender and Human rights**

---

## 📊 Data Source

* **Dataset:** [World Bank Sovereign ESG Data Portal](https://esgdata.worldbank.org/)
* **Scope:** Multi-country panel dataset spanning key Environmental, Social and Governance indicators from **1960 to 2025**.
* **Core Indicators Analyzed:**
  * **Environmental ($E$):** $CO_2$ emissions per capita, Total greenhouse gas emission per capita, Emission of Methane and Nitrous oxide, Fossil fuel energy consumption, Population density, Food Production Index,  Agricultural land and Forest area.
  * **Social ($S$):**  Literacy rate, Fertility rate, Mortality rate, access to clean water/sanitation, Access to electricity, income inequality (Gini index) and Unemployment.
  * **Governance ($G$):** GDP, Economic and Social rights perfomance score and institutional capability metrics.

---


## 📌 Executive Summary & Key Analytical Takeaways

The **World Bank Sovereign ESG Framework (2015–2023)** analysis reveals significant regional divergences across environmental impact, social resilience, and economic equity:

* **Environmental & Climate Vulnerability:** While global emissions briefly dipped during COVID-19 (2020), North America leads per-capita emissions across all GHGs. Agricultural-heavy regions (South Asia) dominate methane ($CH_4$) and nitrous oxide ($N_2O$) outputs.
* **Service Access & Quality of Life:** Basic services (electricity access) show rapid regional convergence (e.g., India approaching ~100%, Bangladesh jumping from <75% to 99%). However, critical infrastructure gaps remain in safely managed drinking water (25% gap in India).
* **Demographic & Human Development Shifts:** Declining fertility rates (India falling to 2.0) signal impending demographic shifts. Developed regions show saturated literacy (~100%), while regional mortality remains heavily skewed (Sub-Saharan Africa mortality is 3x higher than South Asia).
* **Economic Inequality & Sovereign Risk:** Income distribution varies drastically within regions; while India maintains a low Gini index (~25), neighboring economies like Sri Lanka (38) show elevated inequality risks.

---

<details>
<summary><b>🔍 Click to expand complete indicator-by-indicator analysis (14 Categories)</b></summary>

<br>

### 🌿 Pillar 1: Environmental Indicators

* **I. Emission & Pollution:** 
  * Per-capita $CO_2$ dropped sharply in 2020 due to COVID-19 lockdowns, rebounded in 2021, and has since maintained a downward trajectory.
  * North America records dangerously high per-capita total GHG, $CO_2$, $CH_4$, and $N_2O$ emissions.
  * South Asia ranks second in $CH_4$ and $N_2O$ emissions, driven by agriculture, livestock, and waste management.
* **II. Energy Use & Security:** 
  * Economies like Japan, Netherlands, Poland, and Turkiye remain among the top consumers of fossil fuels.
  * Sub-Saharan Africa, South Asia, and North America lead in renewable electricity output, accounting for **55%** of global renewable output.
* **III. Climate Risk & Resilience:** 
  * Arid regions experience severe freshwater stress, while polar regions report near-zero water stress.
  * South Asia exhibits the highest median population density (~400 people/sq. km), elevating climate exposure risks.
* **IV. Food Security:** 
  * Food production indices in Bhutan and Maldives fluctuate significantly, whereas India and Nepal showed steady growth through 2022 before a brief drop in 2023.
  * Sub-Saharan Africa holds the largest agricultural land area as a percentage of total land.
* **V. Natural Capital Management:** 
  * East Asia & Pacific and Latin America lead in forest area percentage; the MENA region holds the least.

---

### 👥 Pillar 2: Social Indicators

* **VI. Access to Services:** 
  * **Electricity:** Maldives achieved 100% access by 2015; Bhutan and Sri Lanka reached it by 2018. Bangladesh expanded access rapidly from <75% (2015) to ~99% (2023). India is near 100%.
  * **Drinking Water:** Safely managed drinking water in India is growing slowly, leaving ~25% of the population unserved in 2023.
* **VII. Demography:** 
  * **Life Expectancy:** Europe & Central Asia leads; Sub-Saharan Africa trails lowest. India's life expectancy dropped sharply during COVID-19 (2020–2021) but recovered to 72 years in 2023.
  * **Fertility:** India's fertility rate dropped to **2.0** in 2023, driven by urbanization and female education/empowerment.
* **VIII. Education:** 
  * Developed regions have hit the 98–100% literacy ceiling. In South Asia, Maldives leads while India holds a median literacy rate of ~78%.
* **IX. Employment:** 
  * India's unemployment rate decreased steadily, reaching **4.2%** in 2023.
* **X. Health & Nutrition:** 
  * Sub-Saharan Africa records a mortality rate of 67.3 (nearly 3x South Asia's 23.0). India demonstrates a linear reduction in mortality from 2015 to 2023.
* **XI. Poverty & Inequality:** 
  * **Gini Index:** India maintains the lowest income inequality in South Asia (~25), compared to Sri Lanka (38) and Bhutan.
  * **Poverty:** South Sudan, Madagascar, and Honduras report the highest poverty headcount ratios globally.

---

### 🏛️ Pillar 3: Governance Indicators

* **XII. Economic Environment:** 
  * **Top Performers:** Guyana led global average annual GDP growth (19.85%), followed by Turks and Caicos Islands (14.28%).
  * **Bottom Performers:** Venezuela, South Sudan, Yemen, and Equatorial Guinea recorded severe negative GDP growth trajectories.
* **XIII. Gender Alignment:** 
  * The proportion of seats held by women in the Indian Parliament has trended upward following the 2019 general elections and subsequent parliamentary cycles.
* **XIV. Human Rights Performance:** 
  * Maldives leads South Asia in Economic and Social Rights scores (~4.6/5.0), whereas India scores 2.8.

---


</details>

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python
* **Data Wrangling:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib, Plotly Express
* **Environment:** VS Code

---


## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sreeragkp222/Decoding-the-Sovereign-ESG-Framework-Capstone-Project.git
   cd Decoding-the-Sovereign-ESG-Framework-Capstone-Project
---

👨‍💻 Author
Sreerag KP
Data Analyst
