# Chronic Absenteeism Trajectory Clustering

This project applies time-series clustering to analyze chronic absenteeism rates across schools using K-Means clustering with Dynamic Time Warping (DTW).

## Dataset
- School-level chronic absenteeism rates (%)
- 17 time points from 2020 to 2025
- Data collected 3 times per academic year

## Methods
- Unsupervised learning with TimeSeriesKMeans (DTW)
- Python packages: tslearn, pandas, matplotlib, seaborn

## Results
- Identified 3 distinct absenteeism trajectory clusters:
  - Cluster 3: consistently low absenteeism (~10%)
  - Cluster 1: stable moderate absenteeism (~30%)
  - Cluster 2: persistently high absenteeism (70-80%) with recent signs of improvement

## Repository Contents
- `ML attendance.ipynb`: full analysis notebook
- Data file: attd_wide.xlsx
- Sample plots and evaluation included in the notebook

## License
This repository is shared for educational purposes.
