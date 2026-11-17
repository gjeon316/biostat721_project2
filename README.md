# BIOSTAT 721 - Project 2: Air Quality Analysis
Author: Gaeun Jeon
Date: November 17, 2026

## Purpose
This project analyzes daily air pollutants (Carbon Monoxide, PM2.5, and Ozone) in Durham County, North Carolina, from 2018 through 2020 to help research for the effects on pain in sickle cell disease.

## Data Source
Pollutant measurements were obtained from the EPA air pollution monitor at the RDU airport, covering years 2018 to 2020 (with 2020 data spanning to the end of April).

## File Structure
- `project2_output.Rmd`: main R Markdown source file containing all data processing, tables, and plots
- `data`: folder containing the raw CSV files (`AQ_2018.csv`, `AQ_2019.csv`, `AQ_2020.csv`).
- `README.md`: project documentation.

## How to Reproduce
1. Ensure R and RStudio are installed.
2. Install the required R packages by running:
   ```r
   install.packages(c("tidyverse", "lubridate", "gt"))
   ```
3. Set the ozone unit in the setup chunk, under the libraries.
4. Knit