# Palworld Game Data Analysis

This repository contains a complete exploratory **data analysis project on Palworld creature data**, using data obtained from Palworld.gg.  
It was completed as part of an undergraduate Data Fundamentals course and showcases my ability to work with semi-structured, real-world game data, clean it, visualize it, and extract gameplay-relevant insights.

📄 **Project Report (HTML):**  
- `Group_Project.html`

---

## 📌 Project Overview

The dataset contains information about many Pals in Palworld, including:

- Elements / Types  
- Combat stats: HP, Attack, Defense, Support  
- Work Suitability (e.g., Mining, Farming, Handiwork, Medicine)  
- Partner skills and passives  
- Breeding-related attributes  

The goal of the project is to understand:

- Which Pals are strongest in combat  
- Which Pals are best suited for base-building and work roles  
- How different stats and attributes correlate with each other  
- What patterns exist among Pal types and roles

---

## 🔍 Key Analyses

### 1. Data Cleaning & Preprocessing
- Standardized column names and formats  
- Handled missing or inconsistent values  
- Parsed long text columns into more structured pieces where needed  
- Prepared numeric columns (HP, Attack, Defense, Work Suitability scores) for analysis

### 2. Exploratory Data Analysis (EDA)
- Distribution of combat stats (HP, Attack, Defense, Support)  
- Distribution of work suitability scores across different tasks  
- Counts and proportions of different Pal elements / types  
- Identification of outlier Pals with extreme stats  

### 3. Visualizations
- Histograms of key stats  
- Bar charts for top-performing Pals in different categories  
- Scatterplots comparing offensive vs defensive capability  
- Plots to help separate Pals by combat vs utility roles  

### 4. Gameplay-Relevant Insights
- Highlighted Pals that are strong “all-rounders”  
- Identified Pals that are especially good for work (e.g., farming, mining)  
- Compared offensive-focused Pals vs tanky/defensive Pals  
- Discussed how players might use these insights when choosing team compositions

---

## 📂 Repository Contents

- `Group_Project.html`  
  Full project report including all analysis, code outputs, and visualizations.

- `Group_Project.ipynb` *(optional)*  
  Jupyter Notebook version of the analysis, if included.

---

## 🛠 Technologies Used

- Python  
- Pandas for data manipulation  
- Matplotlib / Seaborn (or equivalent) for plots  
- Jupyter Notebook for analysis  
- HTML export for sharing the report

---

## 🎮 Context

Palworld is a creature-collection and survival game.  
This project does not simulate gameplay, but instead focuses on **analyzing Pal data** to better understand:

- Stat distributions  
- Roles of different Pals  
- How data-driven insights can inform gameplay decisions.

All data used comes from publicly available sources such as **Palworld.gg**.

Data Fundamentals • Data Analysis • Game Data Exploration

