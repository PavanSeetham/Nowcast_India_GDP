# Nowcast India GDP

This repository contains the code to replicate a research paper titled "[Constructing a Coincident Economic Indicator for India: How Well Does It Track Gross Domestic Product?](https://www.worldscientific.com/doi/pdf/10.1142/S0116110521500104)" by Bhadury et. al 

This project is part of submission for the course Time Series Econometrics at IIT Delhi

The data for this project has been collected from various sources. The data folder contains two excel sheets. 
- 'raw_data_final.xlsx' contains the formatted raw data along with sources. One of the data sources, Government Revenue receipts was not readily available. 

- The file 'govt_revenues_clean' contains a cleaned version of the govt revenue data scraped [CAG, Ministry of Finance website](https://cga.nic.in/MonthlyReport/Published/9/2020-2021.aspx). The code for the scraping can be found in 'scrape_govt_receipts.ipynb'

The notebook 'dfm_india.ipynb' contains the main analsysis. It contains quick explanations along with code.

The pdf file 'Nowcasting.pdf' contains a presentation reviewing the paper by Bhadury et. al
