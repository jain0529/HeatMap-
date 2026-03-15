# Heatmap Hackathon

This repository contains the code for analyzing the proximity and referral chains of non-burn trauma centers to burn centers, developed as part of a Hackathon.

## Project Structure

- `notebooks/`: Contains the Jupyter notebooks used for data analysis and visualization.
  - `Final_HeatMapBurnHack.ipynb`: Main notebook containing the final heatmap and burn center analysis.
  - `Referral_Chain.ipynb`: Analysis of the proximity of non-burn trauma centers to burn centers using geographical distance (Haversine formula).
- `data/`: Directory intended for datasets (e.g., `NIRD 20230130 Database_Hackathon.xlsx`). Note: Data files (.csv, .xlsx) are ignored by git to protect sensitive information or large files from being pushed to the remote repository.

## Setup & Dependencies

To run the notebooks locally, you will need the following libraries:
- `pandas`
- `numpy`
- `pgeocode`

You can install these dependencies using `pip`:
```bash
pip install pandas numpy pgeocode
```
