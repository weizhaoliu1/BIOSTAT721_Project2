# BIOSTAT721_Project2

This repository contains the R project for **BIOSTAT 721 Project 2**.  
The project processes daily air pollution data (CO, PM2.5, O3) from 2018–2020 and produces the required plots and analysis.

---

## Repository Contents

- **BIOSTAT721_Project_2_Weizhao_Liu.Rproj**
- **Project2.Rmd** – main R Markdown report (knits to Word)
- **data/** – raw air quality datasets  
  - `AQ_2018.csv`  
  - `AQ_2019.csv`  
  - `AQ_2020.csv`
- **README.md**

---

## Project Description

This project includes:

### Data Cleaning Function
A function that:
- Renames pollutant variables
- Formats dates
- Removes duplicates
- Averages multiple measurements per day
- Sets negative measurements to zero

### Plots
1. **Monthly CO and O3 averages (with 95% CI)**
2. **Monthly PM2.5 concentrations by year**

---

## GitHub Repository

https://github.com/weizhaoliu1/BIOSTAT721_Project2
