

# Land Surface Temperature Modeling with Urban Sprawl Impact Analysis (Synthetic Data)

## 📌 Project Overview

This project models **Land Surface Temperature (LST)** variations caused by **urban sprawl** and its impact on the **local climate** using synthetic remote sensing data. It combines **urban expansion metrics**, **vegetation cover**, and **land use change indicators** to estimate temperature variations and identify potential urban heat islands.

## 🎯 Objectives

* Simulate synthetic **remote sensing datasets** for LST, NDVI, and urban sprawl indicators.
* Apply **machine learning regression models** to predict LST.
* Analyze **urban sprawl’s influence** on local climate patterns.

## 📂 Data Description

The synthetic dataset contains:

* **NDVI**: Simulated vegetation index from synthetic Sentinel-2 data.
* **Urban Sprawl Index**: Percentage of built-up area per grid cell.
* **LST**: Synthetic land surface temperature values.
* **Elevation**: Terrain influence factor.

## 🛠️ Methodology

1. Generate synthetic LST and urban sprawl data.
2. Calculate vegetation and land use indicators.
3. Train an ML regression model (Random Forest) for LST prediction.
4. Analyze urban sprawl’s effect on temperature variations.

## 📊 Tools & Technologies

* **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* **Synthetic Data Generation** (NumPy random distributions)
* **Visualization** (heatmaps, scatter plots, regression analysis)

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/LST_Urban_Sprawl_Impact.git
   cd LST_Urban_Sprawl_Impact
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:

   ```bash
   python main.py
   ```

## 📈 Expected Output

* Predicted **LST maps** under different urban sprawl scenarios.
* **Scatter plots** showing relationship between NDVI, urban sprawl, and LST.
* **Feature importance** ranking for model variables.




