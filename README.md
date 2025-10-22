## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project builds a multiple linear regression model to predict daily demand for shared bikes, helping BoomBikes understand demand factors post-pandemic.
- The business goal is to enable BoomBikes to optimize inventory and marketing based on predicted demand affected by factors like season, temperature, weather, and year.
- The dataset utilized contains daily bike rental counts along with meteorological and calendar information from a US bike-sharing service.

## Conclusions
- Temperature, year (2018 vs 2019), and seasonal variations significantly influence bike demand.
- Categorical factors like weather condition and season captured using dummy variables contribute meaningfully to predictions.
- Residual analysis validated linear regression assumptions ensuring robust model performance.
- The model explains a significant portion of the variance in demand (R² > 0.7 on test data).

## Technologies Used
- Python 3.9
- Pandas 1.4.2
- Scikit-learn 1.1.0
- Matplotlib 3.5.1
- Seaborn 0.11.2
