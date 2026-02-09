# Data-analysis-on-COVID-19-USING-R


---

## 🦠 COVID-19 Impact Analysis Using R

This project analyzes the **global and country-level impact of COVID-19** using the **COVID19 R package**. The analysis explores **temporal trends**, **country comparisons**, and **regional patterns**, with a focus on understanding how confirmed cases, deaths, and recoveries evolved over time.

---

## 🔍 Project Objectives

* Analyze COVID-19 **confirmed cases, deaths, and recoveries**
* Examine **time-series trends** during different pandemic phases
* Compare pandemic progression across:

  * Countries (Italy vs France)
  * Regions within Italy (Campania vs Veneto)
* Visualize recovery vs mortality trends (Germany case study)

---

## 📦 Data Source

* **COVID-19 Data Hub** via the `COVID19` R package
* Provides standardized global COVID-19 data at multiple geographic levels
* Includes epidemiological indicators and government response indices

> Data citation is included automatically when loading the package.

---

## 🧹 Data Preparation

Key preprocessing steps include:

* Conversion of date fields to proper `Date` format
* Replacement of missing values in critical variables (confirmed, deaths, recovered)
* Validation of dataset structure and summary statistics
* Filtering by country and administrative level for targeted analysis

✔ Result: A clean and consistent dataset suitable for descriptive and comparative analysis.

---

## 📈 Analysis Overview

### 1. Italy: National Trends

* Cumulative confirmed cases show:

  * Slow growth during early 2020
  * Sharp increases during major waves (late 2021–early 2022)
  * Gradual flattening from 2023 onward

### 2. Country Comparison: Italy vs France

* Both countries exhibit similar multi-wave patterns
* France experiences a steeper rise in cumulative cases during peak periods
* Post-2022 trends suggest improved pandemic control in both countries

### 3. Regional Comparison within Italy

* Comparison between **Campania** and **Veneto**
* Both regions show:

  * Steady cumulative growth
  * Pronounced surges during major pandemic waves
  * Slower growth in later periods

### 4. Germany: Recoveries vs Deaths

* Recoveries far exceed deaths throughout the pandemic
* The widening gap over time suggests:

  * Improved treatment outcomes
  * Expanded vaccination coverage
  * Lower fatality rates in later stages

---

## 📊 Visualizations

The project includes multiple `ggplot2` visualizations:

* Time-series line plots of confirmed cases
* Country-level comparison plots
* Regional trend comparisons
* Recovered vs death case trajectories

All plots are generated using a minimal and consistent visual style.

---

## 🛠️ Tech Stack

* **R**
* RStudio
* R Markdown
* `COVID19`
* `tidyverse` (dplyr, ggplot2, tidyr)
* `lubridate`

---

## 📁 Suggested Repository Structure

```
├── data/                 # (optional) exported datasets
├── figures/              # generated plots
├── analysis.Rmd          # R Markdown source
├── analysis.html         # knitted report
├── README.md
```

---

## ⚠️ Notes & Limitations

* COVID-19 data is cumulative and reporting practices vary by country
* Some variables contain missing values depending on region and time period
* This analysis is **descriptive**, not predictive or causal

---

## 🚀 Possible Extensions

* Normalize cases by population size
* Include vaccination trend analysis
* Add mortality rate and case-fatality ratios
* Extend comparisons to additional countries or regions

---


