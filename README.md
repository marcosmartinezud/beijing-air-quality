# Beijing Air Quality - AML Project

This repository contains the project for the **Advanced Machine Learning** course. We are using the Beijing Air Quality dataset (2013-2017) to build and test forecasting models.

## Objectives
The goal is to predict air pollution levels with a 24 to 72-hour horizon.
* **Primary Target:** PM2.5 concentration.
* **Secondary Targets:** We will also try to forecast NO2 and CO to test a multivariate approach.

## Project Structure
* `data/`: Place the raw CSV files here (ignored by git).
* `notebooks/`: Jupyter notebooks for EDA and model testing.
* `src/`: Final Python scripts and helper functions.

## Getting Started
1. Clone the repo.
2. Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate