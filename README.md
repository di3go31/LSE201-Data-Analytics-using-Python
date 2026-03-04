# LSE Data Analytics using Python

## Quick Access

- [Python notebook](Python_analysis/JimenezLopez_DiegoEnrique_DA201_Assignment_Notebook.ipynb)
- [Full analysis with outputs](Python_analysis/JimenezLopez_DiegoEnrique_DA201_Assignment_Notebook.pdf)
- [Technical report](Technical_project/JimenezLopez_DiegoEnrique_LSEDA201_technical_report.pdf)

## Project

Python analysis project from the LSE Data Analytics programme examining NHS appointment volumes across service settings and seasons.

## Business Problem

NHS stakeholders disagree on whether pressure on the system reflects insufficient capacity or inefficient use of existing facilities.

## Objective

Analyse appointment activity across service settings and seasonal periods to identify patterns in demand and capacity utilisation.

## Data

Four datasets provided by the course:

- appointments_regional.csv – appointment volumes by region and service setting  
- national_categories.xlsx – service category definitions  
- actual_duration.csv – consultation duration distributions  
- tweets.csv – supplementary contextual data  

Additional contextual information obtained by scraping NHS publications.

## Method

- Clean datasets with pandas  
- Standardise date formats and identifiers  
- Merge datasets to combine volumes, categories and duration data  
- Aggregate appointment volumes by service setting and time period  
- Create derived metrics describing workload distribution  
- Visualise patterns using matplotlib

## Findings

General Practice handles the majority of appointments even when demand shifts seasonally across other services.  
This indicates strong structural reliance on General Practice within the NHS appointment system.

## Tools

Python  
pandas  
NumPy  
matplotlib  
Jupyter Notebook
