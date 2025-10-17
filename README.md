# Programming Assignment 2

Author: Eli Freedman<br>
Course: MSDS 451: Financial Engineering<br>
Date: October 19, 2025

## Overview

This assignment investigates simulating returns for varying assets using either only long positions, or long and short positions. The simulation is performed on two different sets of assets. The first set, denoted as `set_1` throughout the notebook, is dummy data collected from the jumpstart code provided by Professor Miller. The second set, `set_2`, is made up of four equities: Procter & Gamble (`$PG`), Coca-Cola (`$KO`), PepsiCo (`$PEP`), and Costco (`$COST`). These equities were used specifically because they are used for my final project consumer staples ETF.

## Structure

`README.md`: Contains all information required to understand and run this assignment<br>
`requirements.txt`: All Python modules used in this assignment<br>
`programming_assignment_2.ipynb`: Code used to develop the predictive model<br>
`programming_assignment_2.html`: HTML version of the notebook (better viewing)<br>
`PG_historical_data.csv`: Historical data of the $PG ticker from 2005-2025<br>
`KO_historical_data.csv`: Historical data of the $KO ticker from 2005-2025<br>
`PEP_historical_data.csv`: Historical data of the $PEP ticker from 2005-2025<br>
`COST_historical_data.csv`: Historical data of the $COST ticker from 2005-2025<br>
`monte_carlo_results_set_1`: Graph displaying monte carlo simulation results for the dummy assets<br>
`monte_carlo_results_set_2`: Graph displaying monte carlo simulation results for Procter & Gamble (`$PG`), Coca-Cola (`$KO`), PepsiCo (`$PEP`), and Costco (`$COST`)

## Set Up

1. Ensure you are running Python 3.12 or later. This project was developed using 3.12, so it may not be compatible with previous versions.
2. Create a virtual environment by executing `python -m venv .venv`
3. Enter the virtual environment
4. Download the requirements by executing `pip -r requirements.txt`
5. Run all cells in the `programming_assignment_2.ipynb` notebook

## AI Usage

1. Assisted in translating jumpstart R code to Python.
2. Assisted in capturing daily volatility and converting to annual volatility.