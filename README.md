# MasterThesis

## Repository Structure Overview

This repository contains code and data processing scripts related to the Master Thesis "Deforestation Monitoring Using Machine Learning Models and Time-Series Satellite Data"

### Exported Satellite Imagery
- Files starting with `export_all_...`  
  → Contain exported spectral bands and vegetation indices from **Sentinel-2** and **Landsat 8** imagery.

### Dataset Construction
- Files starting with `npz_pipeline_...`  
  → Construct the final **machine learning dataset** (`.npz` format) based on satellite vegetation indices and band composites.

### Machine Learning Models
- All other `.ipynb` files  
  → Contain the source code for various **ML models**, including training, evaluation, and inference routines.

### Results and Evaluation
- Folder: `Metrics/`  
  → Includes **performance metrics**, confusion matrices, and visualizations for trained ML models.
