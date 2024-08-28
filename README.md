# MTA SUBWAY Data Analysis

## Overview
This project aims to determine which subway stations the teams distributing promotional brochures should be stationed
at for a gala event that raises awareness about unemployment and organizes a donation campaign.
The NYC MTA Subway Hourly Ridership dataset has been utilized for this purpose.
Additionally, the Unemployment Insurance Beneficiaries dataset has been examined
as supporting data.

_Dataset Link_: https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-Beginning-February-202/wujg-7c2s/
## Project Structure


- **[subway_research.ipynb](subway_research.ipynb)**: The Jupyter Notebook file where the data is examined and analyzed
- **[MTA SUBWAY.pdf](MTA%20SUBWAY.pdf)**: The presentation file explaining the project and its key findings
- **[subway_map_updated.html](subway_map_updated.html)**: The file displaying the selected stations on a map according to their importance level
- **[Unemployment...csv](Unemployment_Insurance_Beneficiaries_and_Benefit_Amounts_Paid__Beginning_2001_20240316.csv)**: Dataset for supplementary observations.

## Requirements

Make sure to install the required packages before running the script:

```bash
pip install -r requirements.txt
```

The required packages are:

- numpy==1.26.4
- pandas==2.2.1
- matplotlib==3.8.3
- seaborn==0.13.2
- folium==0.16.0
