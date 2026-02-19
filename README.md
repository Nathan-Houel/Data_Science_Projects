# **Data Science Projects Portfolio**

Welcome to my collection of Data Science projects! This repository contains various analyses performed using Python and its data science ecosystem. Each project explores different datasets and answers specific questions through data cleaning, processing, and visualization.

## Table of Contents
* [📁 Structure](#-structure)
* [📈 California Cities: Area & Population](#1-california-cities-area--population)
* [🚲 Seattle Bicycle Counts Analysis](#2-seattle-bicycle-counts-analysis)
* [🎂​ US Birth Rate Analysis](#3-us-birth-rate-analysis)
* [👨‍💼​ US President Heights Analysis](#4-us-president-heights-analysis)
* [🛠️ Installation & Requirements](#installation--requirements)

---

## 📁 Structure

```
├── 📁 Area and Population
│   ├── 📁 data
│   │   └── 📄 california_cities.csv
│   ├── 📄 Area_and_Population.ipynb
│   └── 🖼️ Output.png
├── 📁 Bicycle Counts
│   ├── 📁 data
│   │   └── 📄 fremont-bridge.csv
│   ├── 📄 Bicycle_counts.ipynb
│   └── 🖼️ Outputs.png
├── 📁 Birth Rate Analysis
│   ├── 📁 data
│   │   └── 📄 births.csv
│   ├── 📄 Birth_Rate.ipynb
│   ├── 🖼️ Output_3.png
│   └── 🖼️ Outputs.png
├── 📁 President Heights
│   ├── 📁 data
│   │   └── 📄 president_heights.csv
│   ├── 🖼️ Output.png
│   └── 📄 President_heights.ipynb
├── 📝 README.md
└── 📄 requirements.txt
```


## 📈 California Cities: Area & Population

**Location:** `Area and Population/`

This project analyzes the relationship between the area and population of cities in California. Using geographic data (latitude and longitude), we visualize the distribution of cities, where the size and color of the points represent the area and population, respectively.

* **Key Libraries:** Pandas, Matplotlib, Seaborn, Numpy.
* **Data Source:** `california_cities.csv`

### 📊 Results
![California Cities Analysis](./Area%20and%20Population/Output.png)

---

## 🚲 Seattle Bicycle Counts Analysis

**Location:** `Bicycle Counts/`

An analysis of bicycle traffic across Seattle's Fremont Bridge. This project deals with time-series data to understand biking trends. We perform data resampling and calculate rolling means to visualize the weekly traffic trends between the East and West sidewalks.

* **Key Libraries:** Pandas, Matplotlib, Seaborn.
* **Data Source:** `fremont-bridge.csv`

### 📊 Results
![Bicycle Counts Visualization](./Bicycle%20Counts/Outputs.png)

---

## 🎂​ US Birth Rate Analysis

**Location:** `Birth Rate Analysis/`

This project explores US birth data spanning several decades. It involves significant data cleaning (handling dates and missing values) to analyze trends in birth rates by gender and decade.

* **Key Libraries:** Pandas, Matplotlib, Seaborn, Numpy.
* **Data Source:** `births.csv`

### 📊 Results
![Birth Rate](./Birth%20Rate%20Analysis/Outputs.png)
![Birth Rate Trends](./Birth%20Rate%20Analysis/Output_3.png)

---

## 👨‍💼​ US President Heights Analysis

**Location:** `President Heights/`

A statistical analysis of the heights of US Presidents. This notebook calculates summary statistics (mean, standard deviation, percentiles) and visualizes the distribution of heights. It also includes a linear regression to estimate trends in presidential heights over time.

* **Key Libraries:** Pandas, Matplotlib, Seaborn, Numpy.
* **Data Source:** `president_heights.csv`

### 📊 Results
![President Heights Distribution](./President%20Heights/Output.png)

---

## 🛠️ Installation & Requirements

To run these notebooks locally, you will need Python installed along with the following libraries:

```bash
python -m venv .venv
.venv/source/activate
pip install -r requirements.txt
```

## 👤 Contact

Nathan Houel - houel.nathan.18@gmail.com  

Project link: [Data Science Projects Portfolio](https://github.com/Nathan-Houel/Data_Science_Projects)