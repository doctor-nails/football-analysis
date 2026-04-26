# Football AI

## Description
This project implements an AI system for analyzing and predicting football (soccer) match outcomes using machine learning techniques.

##  Dataset
- **Source**: [Kaggle - International Football Results (1872-2024)](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)
- **Size**: 40,000+ matches
- **Time Period**: 1872 - 2024
- **Includes**: Home team, away team, home score, away score, date, tournament, city, country

## Features
- Data collection from football APIs
- Model training for match prediction
- Visualization of results

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/username/football-ai.git
    ```
2. Install dependencies:
    ```
    pip install -r requirements.txt


    ```

## Setup 

: Download the Dataset
Download results.csv from Kaggle:

Go to: https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017

Click "Download"

Place results.csv in the project root folder

Set Up Virtual Environment
On Linux/macOS (including Arch Linux):

# Create virtual environment
python -m venv .venv

# Activate virtual environment
source .venv/bin/activate

# You should see (.venv) in your terminal prompt


On Windows:

# Create virtual environment
python -m venv .venv

# Activate virtual environment
.venv\Scripts\activate

# You should see (.venv) in your command prompt

# Install Dependencies
With the virtual environment activated:

bash
# Install required packages
pip install -r requirements.txt

# Verify installation
pip list

# Run the Analysis

# Make sure virtual environment is activated
source .venv/bin/activate  # Linux/macOS
# OR
.venv\Scripts\activate     # Windows

# Run the analysis script
python football_analysis.py

## Contributing
Feel free to submit issues and pull requests.

## License
MIT License