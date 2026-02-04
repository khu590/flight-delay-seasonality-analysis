# US Flight Delays: Seasonal Pattern Analysis

## Overview
This project investigates whether flight delays in the United States follow a seasonal pattern across the year. Using 6.2 million domestic flight records from 2020, the analysis confirms clear seasonality, with higher delays during summer and December, and lower delays in early months of the year.

## Dataset
**Source**: Kaggle – US National Flight Data 2015–2020  
https://www.kaggle.com/datasets/bingecode/us-national-flight-data-2015-2020

**Scope**
- Year analysed: 2020  
- Records: ~6.2 million flights  
- Key attributes: month, departure delay, arrival delay  

Only the 2020 subset was used for this study.

## Methodology
- Filtered the dataset to retain relevant delay and time attributes  
- Handled missing values using median imputation  
- Aggregated arrival and departure delays by month  
- Generated an interactive visualization to compare seasonal trends  
- Interpreted monthly patterns to identify peak and low delay periods  

## Key Findings
- Flight delays show a clear seasonal pattern across the year  
- Highest average delays occur during June–August and December  
- Lowest delays are observed between January and March  
- Arrival and departure delays follow similar monthly trends  

## Visualization
The final output is an interactive Plotly grouped horizontal bar chart showing average monthly arrival and departure delays. The visualization includes seasonal background bands, hover tooltips for precise values, and a color-blind friendly palette to improve accessibility and interpretation.

<img width="1225" height="804" alt="image" src="https://github.com/user-attachments/assets/55f21c0a-598f-40c7-80c3-2772cc78a80f" />


## Technologies Used
- Python  
- Pandas  
- Matplotlib  
- Plotly  
- Jupyter Notebook  
- Google Colab  

## How to Run
```bash
git clone https://github.com/khu590/flight-delay-seasonality-analysis.git
cd flight-delay-seasonality-analysis
pip install -r requirements.txt
