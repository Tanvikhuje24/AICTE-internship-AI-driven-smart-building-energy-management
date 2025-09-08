# AI-driven Smart Building Energy Management

This project demonstrates forecasting building energy consumption using AI/ML models.

## Dataset
- Synthetic dataset generated with features:
  - Temperature
  - Humidity
  - Occupancy
  - Appliances Load
  - Energy Consumption (target)

## Workflow
1. Data preprocessing & EDA
2. Feature selection
3. Model training (Linear Regression, Random Forest)
4. Model evaluation
5. Save trained Random Forest model

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Smart_Building_Energy_Management.ipynb
```

## Files
- building_energy_data.csv : dataset
- Smart_Building_Energy_Management.ipynb : notebook
- requirements.txt : dependencies
- rf_energy_model.pkl : trained Random Forest model (generated after running notebook)
