## Influenza Transmission Dynamics in the Republic of Korea (Pre- and Post-COVID-19)
This repository contains the data and code used in our study titled: "Season-specific influenza transmission dynamics before and after the COVID-19 pandemic in the Republic of Korea: An ensemble Kalman filter approach.

## Overview
This project employs an Ensemble Kalman Filter (EnKF) approach to model and analyze the shifts in influenza transmission dynamics in the Republic of Korea. The study specifically investigates the changes in seasonal transmission patterns before and after the emergence of the COVID-19 pandemic, providing insights into how public health interventions and behavioral changes influenced influenza circulation.

## Data Availability
The raw daily influenza data can be obtained from the source below:
Raw data: https://www.data.go.kr/data/15089429/fileData.do
The processed data used in this study are provided in ‘main/Data/influenza_data.xlsx’ including daily influenza case counts, absolute humidity, and influenza proportion.

## Repository Structure
The following files and directories are included in this repository:

/Data: Contains pre-processed influenza data from the Republic of Korea used in our analysis.

/Results: Contains the seasonal estimates obtained using the Ensemble Kalman Filter (EnKF) from the influenza data of the Republic of Korea (2016/17, 2017/18, and 2022/23 season).

Figure.py: The primary execution script to reproduce the study's results.

/Figures: Contains the generated figures.
