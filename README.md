## Forest Fire Size Prediction
### 📌 Project Overview

This project predicts forest fire damage areas using environmental and fire-related data.
The goal is to support fire impact forecasting, resource management, and public safety.
The pipeline includes data preprocessing, outlier removal, feature importance analysis, clustering, and visualization to categorize damage severity.

### 📂 Dataset Composition

**Features included:**

occurgm — Region of fire occurrence

occurdt — Year of fire occurrence

extingtm — Time taken to extinguish fire

tempavg — Average temperature

windavg — Average wind speed

rainamount — Rainfall amount

raindays — Number of rainy days

humidrel — Relative humidity

dmgarea — Fire damage area

Size: 3948 samples → reduced to 2923 after outlier removal

### ⚙️ Workflow

Data Cleaning – Outlier removal, handling missing & zero values

Feature Importance – Random Forest to rank environmental variables

Clustering – KMeans with 5 clusters (Negligible → Severe damage)

Visualization – Histograms, cluster distribution, silhouette analysis

### 📊 Results

Optimal clusters: 5 (Elbow method)

Categories: Negligible, Minor, Moderate, High, Severe Damage

Silhouette Score: ~0.69 (good separation)
