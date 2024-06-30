# Hedging Comparison

This repository contains an R script to compare static and dynamic hedging strategies for gasoline prices using historical spot and futures prices. The script calculates and visualizes the hedged returns and their variances to analyze the effectiveness of each hedging strategy.

## Data

The dataset used in this project contains the following columns:
- `Date`: The date of the observations.
- `NY_spot`: New York spot prices of gasoline.
- `NY_Futures`: New York futures prices of gasoline.

Ensure your dataset is named `Gasoline_spot` and has the columns mentioned above.

## Requirements

The script requires the following R packages:
- `dplyr`
- `ggplot2`
- `zoo`
