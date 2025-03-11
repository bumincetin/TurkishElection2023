# Turkish Parliamentary Elections Prediction Model

## Overview
This repository contains the research and implementation of predictive techniques for Turkish Parliamentary Elections. The project focuses on developing and evaluating various forecasting models to predict election outcomes using historical data, polls, and socio-economic indicators.

## Project Structure

### Data Files
- `polls_for_2023.csv`: Recent polling data for 2023 elections
- `party_results.csv`: Historical party election results
- `presidency_polls_2023.csv`: Presidential election polling data
- Geographic Data Files (TUR_adm*.*)`: Shape files for Turkish administrative regions
- Various socio-economic indicator files:
  - Education levels
  - Household statistics
  - Median age demographics
  - Well-being indices

### Analysis Notebooks
- `election_seats_prediction_2023_FundamentalModel.ipynb`: Main model for predicting parliamentary seats
- `general_election_percentage_prediction_2023.ipynb`: Vote percentage predictions
- `presidential_election_percentage_prediction_2023.ipynb`: Presidential election analysis

### Research Papers
The `papers/` directory contains relevant academic literature and research papers that form the theoretical foundation of this work.

## Methodology
The prediction models incorporate multiple data sources:
1. Historical election results
2. Recent polling data
3. Demographic indicators
4. Socio-economic factors
5. Geographic information

## Requirements
To run the analysis notebooks, you'll need:
- Python 3.8+
- Jupyter Notebook
- Required Python packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - geopandas
  - scikit-learn

## Usage
1. Clone this repository
2. Install required dependencies
3. Open the Jupyter notebooks in the `data/` directory
4. Execute the cells to reproduce the analysis

## Data Sources
- Turkish Statistical Institute (TurkStat)
- Electoral polling organizations
- Official election results from YSK (Supreme Election Council)
- Various socio-economic databases

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Authors
- Bumin Can Korkut

## Acknowledgments
Special thanks to all the organizations and researchers who made their data publicly available for this analysis. 