# 🇨🇦 Employment Trends Analysis in Canada

## 📝 Overview
This project investigates employment trends in Canada by comparing the **pre-pandemic period (2015–2019)** to the **post-pandemic period (2020–2024)**. Using data cleaning, visualization, and analysis techniques in R, this study identifies changes in employment patterns due to the COVID-19 pandemic.

## 📊 Dataset
- **File Used**: `employment_trends.csv`  
- **Source**: [Employment Trends](https://www.kaggle.com/datasets/noeyislearning/employment-trends)  
- **Time Period**: January 2015 to December 2024  
- **Data Includes**: Monthly employment figures across multiple sectors and provinces.

## 🛠️ Tools & Libraries
This project was built using **Quarto** with code written in **R**. The following libraries are used:

- `tidyverse`
- `kableExtra`
- `ggplot2`
- `dplyr`

## 📂 Contents
- **Data Cleaning**: Filters irrelevant units and missing values.
- **Data Transformation**: Creates a new `Period` variable to group data as Pre-Pandemic vs. Post-Pandemic.
- **Visualization**: Generates comparative plots to highlight employment trends over time.
- **Reporting**: Final output is formatted as a PDF using Quarto.

## ▶️ How to Run
1. Open the `.qmd` file in RStudio.
2. Ensure all required packages are installed.
3. Knit the document to **PDF** using Quarto to generate the final report.
4. Make sure the CSV file path in the script matches your local environment.

## 👥 Authors
- Ya-Nuo, Hsu  
- Kevin Johnson  
- **Date**: December 18, 2024
