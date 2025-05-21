# Solar Challenge Week 1

## Overview

This project analyzes high-resolution solar irradiance and weather data from Benin, Sierra Leone, and Togo to identify optimal zones for solar energy deployment. It includes dataset cleaning, exploratory data analysis (EDA), statistical testing, and cross-country comparison.
## Project Goals
-Clean and validate irradiance and weather datasets.
-Perform country-specific exploratory analysis.
-Compare solar potential across countries using statistical tests.
-Generate actionable insights for solar farm site selection.


##Below is the folder structure: 
SOLAR-FARM-DISCOVERY/
├── .github/workflows/ci.yml              # CI with GitHub Actions
├── .venv/                                # Python virtual environment
├── .vscode/                              # Editor config
├── data/                                 # Raw and cleaned datasets
│   ├── benin_clean.csv
│   ├── sierra_leone_clean.csv
│   ├── togo_clean.csv
│   └── ...
├── notebooks/                            # Jupyter notebooks per task/country
│   ├── benin_eda.ipynb
│   ├── togo_eda.ipynb
│   ├── compare_countries.ipynb
│   └── ...
├── scripts/                              # Modular script directory
│   └── __init__.py
├── tests/                                # Future testing suite
├── .gitignore
├── requirements.txt
└── README.md                             # This file



