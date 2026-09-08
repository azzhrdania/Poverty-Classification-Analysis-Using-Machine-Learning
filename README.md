# Poverty Data Analysis and Exploratory Data Analysis

## Overview

This project focuses on analyzing poverty-related data across districts and cities in Indonesia through **data cleaning and exploratory data analysis (EDA)**. The analysis aims to understand the distribution of poverty levels and the relationships between poverty and several socioeconomic indicators.

The dataset consists of **532 observations and 13 variables**, covering indicators related to education, expenditure, human development, health, sanitation, employment, and regional economic conditions.

## Dataset

The dataset contains the following variables:

| Variable                 | Description                     |
| ------------------------ | ------------------------------- |
| `Provinsi`               | Province                        |
| `KabKota`                | District/City                   |
| `Kemiskinan`             | Poverty level                   |
| `RLS`                    | Mean Years of Schooling         |
| `Pengeluaran`            | Expenditure                     |
| `IPM`                    | Human Development Index         |
| `UHH`                    | Life Expectancy                 |
| `Sanitasi`               | Sanitation                      |
| `AirMinum`               | Access to Drinking Water        |
| `TPT`                    | Unemployment Rate               |
| `TPAK`                   | Labor Force Participation Rate  |
| `PDRB`                   | Gross Regional Domestic Product |
| `Klasifikasi Kemiskinan` | Poverty Classification          |

## Data Cleaning

The dataset was prepared through several data cleaning steps:

* Checking dataset structure and data types
* Identifying missing values
* Removing records containing missing values
* Detecting and handling outliers using the **Interquartile Range (IQR)** method
* Checking and removing duplicate records
* Validating the dataset after cleaning
* Exporting the cleaned dataset for further analysis

## Exploratory Data Analysis

The EDA focuses on understanding:

* Correlation between socioeconomic indicators
* Distribution of poverty levels
* Relationship between expenditure and poverty
* Regions with the highest poverty levels
* Relationship between Human Development Index (IPM) and expenditure

### Key Findings

The analysis indicates that several indicators, including **IPM, expenditure, mean years of schooling (RLS), and life expectancy (UHH)**, generally show a negative relationship with poverty levels.

The analysis also shows a tendency for regions with higher expenditure levels to have lower poverty levels, while regions with higher IPM tend to have higher expenditure levels.

These findings provide an overview of socioeconomic conditions across regions and can serve as supporting information for understanding regional poverty patterns.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Microsoft Excel

## Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ├── Missing Value Handling
   ├── Outlier Detection & Handling
   └── Duplicate Removal
   ↓
Clean Dataset
   ↓
Exploratory Data Analysis
   ├── Correlation Analysis
   ├── Distribution Analysis
   ├── Relationship Analysis
   └── Regional Comparison
```

## Project Structure

```text
├── Azzahra_Dania_Indriyani_LSP.ipynb
├── Dataset_Kemiskinan.xlsx
├── Dataset_Kemiskinan_Clean.csv
└── README.md
```

## Author

**Azzahra Dania Indriyani**

Information Systems Graduate
Interested in Data Analysis and Data Science
