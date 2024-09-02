# Unsupervised-Weather-Anomalies-Detection
Data Science for Public Policy, Project (2) - Columbia University

This repository focuses on detecting weather anomalies, particularly flood events, in the United States using unsupervised machine learning techniques. The analysis is based on data from NOAA's Storm Events Database and includes outlier detection models such as Isolation Forest.

## Project Overview

The goal of this project is to identify anomalous weather patterns, specifically flood events, and analyze their timing, geographic distribution, and impacts. We leverage unsupervised learning methods to detect outlier events and assess their implications.

The key components of the project include:
- Event frequency and distribution analysis
- Flood duration insights
- Anomaly detection using Isolation Forest
- Geographic impact visualization
- Assessment of human impact (fatalities, injuries)

Interactive visualizations are available on Tableau Public.

## Data

The following data sources are used in this project:
- `floods.csv` and `floods.xlsx`: Contains detailed flood event data.
- `storm_events.db`: A database file with comprehensive storm event data.
- `StormEvents_details-ftp_d2023.csv`, `StormEvents_fatalities-ftp_d2023.csv`, `StormEvents_locations-ftp_d2023.csv`: CSV files detailing specific storm events, fatalities, and locations.

## Notebooks

The `Floods_in_US_2023.ipynb` Jupyter notebook contains code for data cleaning, processing, and visualization, including the implementation of unsupervised anomaly detection models.

## Documents

The `DSPP_Final_Project.docx` provides a comprehensive report on the findings of this analysis. Additionally, PDF files (`Storm-Data-Bulk-csv-Format.pdf` and `Storm-Data-Export-Format.pdf`) outline the formats used for the raw data.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Unsupervised-Weather-Anomalies-Detection.git

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
  
3. Run the Jupyter notebook for analysis:
   ```bash
   jupyter notebook notebooks/Floods_in_US_2023.ipynb


