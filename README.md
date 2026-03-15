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

## How to proceed with GitHub

Before you can push this to GitHub, make sure you have created an empty repository on your GitHub account!
1. Go to [github.com/new](https://github.com/new) and **create a new repository**. *Important: Do NOT check the boxes to initialize with a README, .gitignore, or license, since those are already created here.*
2. Copy the URL of your new repository.
3. In your terminal, verify you are inside the `Heatmap Hackathon Codes` directory, and run the following commands (replace `YOUR_GITHUB_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual details):

```bash
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
git push -u origin main
```
