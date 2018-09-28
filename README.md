# Chicago WNV Prediction

This is a group project for the [West Nile Virus Prediction Kaggle Competition](https://www.kaggle.com/c/predict-west-nile-virus).

# EDA:

1. EDA: Basic
    Basic stats.
2. EDA: Map
    Maps of trap results by year.
3. EDA: Graphs
    Plots of trap results over time.
4. EDA: Weather
    Correlation with weather and WNV.

# Model and Predictions


### Cleaning
1. Weather data prep

### Feature Engineering
2. Engineering weather features
    - Rolling averages
    - Combine same-day trap results
3. Location weighting
4. Clustering
5. Combine weather and train datasets
6. Interaction effects

### Munging
7. Undersampling
8. Feature selection
    - Get dummies 
    - Scaling
    - Concat
    - Omit columns not in test dataset
    
### Modeling
9. Train test split
10. Modeling
11. Predict

# Prediction Reader Sanity Check

- Plots WNV predictions over time and map.

# Assets

All datasets for project (from Kaggle download).

# Submission

All Kaggle submission .csv.

---
Viz: https://public.tableau.com/profile/sam.c7069#!/vizhome/ChicagoWNV_0/Map-ChicagoWNV?publish=yes

Slides: https://docs.google.com/presentation/d/16lK1tgRsx71pVeUpVn1VS1ZqgT3O418iS_QGK2pM940/edit?usp=sharing

