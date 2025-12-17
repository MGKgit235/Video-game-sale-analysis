# Video Game Sales Analysis (1980–2016)

## Overview

This project performs an exploratory data analysis of global video game sales from 1980 to 2016. The objective is to identify sales trends across publishers, genres, platforms, regions, and time, while demonstrating practical skills in data cleaning, aggregation, and visualization using Python.

---

## Objectives

* Analyze global sales performance by publisher, genre, and platform
* Compare regional sales patterns across North America, Europe, Japan, and other regions
* Examine top-performing titles from a major publisher (Nintendo)
* Study early industry sales trends over time

---

## Dataset

* **Source:** Kaggle – Video Game Sales Dataset
* **Time Range:** 1980–2016
* **Records:** ~16,500

### Features

* Game title, platform, genre, publisher
* Release year
* Regional sales (NA, EU, JP, Other) in millions
* Global sales in millions

---

## Data Preparation

The dataset was cleaned and prepared using the following steps:

* Removed records with missing release years
* Converted release year to integer format
* Removed records with missing publisher information
* Checked for duplicate entries
* Validated schema and summary statistics

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Analysis Summary

### Sales Concentration

* Identified top 5 publishers by total global sales
* Identified top 5 genres by total global sales
* Identified top 5 platforms by total global sales

### Publisher-Level Analysis

* Analyzed top 10 Nintendo games by global sales

### Regional Analysis

* Evaluated global sales distribution across regions
* Compared North America and Europe sales using filtered scatter analysis

### Time-Series Analysis

* Aggregated and visualized regional sales trends from 1980 to 1995

---

## Key Findings

* Nintendo leads global sales due to strong flagship franchises
* Action, Sports, and Platform genres account for a significant share of total sales
* North America is the largest contributor to global video game revenue
* Japan exhibits distinct sales behavior compared to Western markets
* Early industry growth was gradual, with regional divergence emerging over time

---

## Conclusion

This project demonstrates a structured data analytics workflow, from data cleaning to insight generation through visualization. It highlights proficiency in Python-based exploratory data analysis and the ability to communicate findings clearly using visual tools.

---

## Future Work

* Extend time-series analysis beyond 1995
* Perform deeper genre-wise regional comparisons
* Build interactive dashboards using Power BI or Plotly

---

## Reproducibility

1. Clone the repository
2. Install dependencies: `pandas`, `numpy`, `matplotlib`, `seaborn`
3. Run the Jupyter Notebook to reproduce the analysis
