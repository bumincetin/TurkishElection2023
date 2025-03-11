# Turkish Parliamentary Elections Prediction Model

## Overview
This repository contains research and implementation of predictive techniques for Turkish Parliamentary Elections. The project focuses on developing and evaluating various forecasting models to predict election outcomes using historical data, polls, and socio-economic indicators.

## Repository Structure
```
.
├── data/                   # Data files and analysis notebooks
│   ├── raw/               # Raw data files
│   ├── processed/         # Processed datasets
│   └── notebooks/         # Jupyter notebooks for analysis
├── papers/                # Research papers and documentation
└── requirements.txt       # Python dependencies
```

## Data Files
The `data` directory contains:

### Analysis Notebooks
- `election_seats_prediction_2023_FundamentalModel.ipynb`: Main model for predicting parliamentary seats
- `general_election_percentage_prediction_2023.ipynb`: Vote percentage predictions
- `presidential_election_percentage_prediction_2023.ipynb`: Presidential election analysis

### Datasets
- Electoral Data:
  - `polls_for_2023.csv`: Recent polling data
  - `party_results.csv`: Historical party results
  - `presidency_polls_2023.csv`: Presidential polls
- Geographic Data:
  - `TUR_adm*.shp`: Turkish administrative region shapefiles
- Socio-economic Indicators:
  - Education levels by province
  - Household statistics
  - Demographic data
  - Well-being indices

## Methodology
The prediction models incorporate multiple data sources and techniques:

1. Historical Analysis
   - Past election results
   - Voting pattern trends
   - Regional variations

2. Current Indicators
   - Recent polling data
   - Demographic shifts
   - Socio-economic factors

3. Geographic Analysis
   - Regional voting patterns
   - Administrative boundaries
   - Demographic distribution

## Requirements
To run the analysis notebooks, you'll need:
- Python 3.8+
- Jupyter Notebook
- Required Python packages (see requirements.txt):
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - geopandas
  - scikit-learn

## Setup and Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/bumincetin/TurkishElection2023.git
   cd TurkishElection2023
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebooks in the `data` directory to:
   - View the analysis
   - Run predictions
   - Explore the data

## Data Sources
- Turkish Statistical Institute (TurkStat)
- Electoral polling organizations
- Official election results from YSK (Supreme Election Council)
- Various socio-economic databases

## Research Papers
The `papers` directory contains relevant academic literature that forms the theoretical foundation of this work, including:
- Election forecasting methodologies
- Statistical analysis techniques
- Case studies of electoral predictions
- Social network analysis in election forecasting

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Author
- Bumin Kagan Cetin

## Acknowledgments
Special thanks to all the organizations and researchers who made their data publicly available for this analysis. 