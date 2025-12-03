# **HCHO Emission Prediction for Sri Lanka**

This project focuses on **analyzing and predicting formaldehyde (HCHO) emissions** at various locations in Sri Lanka. The goal is to support **environmental monitoring and air quality assessment** using historical HCHO measurements and predictive modeling.

### **Dataset Overview**

* **Source:** CSV files containing HCHO measurements for Colombo, Kandy, and Monaragala/Bibile.
* **Columns:** Numeric HCHO values, location names, start and end dates.
* **Size:** Varies by location (e.g., Colombo: 5477 rows x 4 columns; Kandy: 1825 rows x 4 columns).

### **Notebook Workflow**

1. **Environment Setup**

   * Google Colab configuration, required library installation (`pandas`, `scikit-learn`, `geopy`, `matplotlib`, `seaborn`).
2. **Data Loading**

   * Load multiple CSVs into pandas DataFrames, inspect shape, head, and missing values.
3. **Exploratory Data Analysis (EDA)**

   * Descriptive statistics, missing value checks, and initial visualizations.
4. **Preprocessing & Feature Engineering** *(inferred)*

   * Parse dates, handle missing values, encode location labels, and potentially create time-based features.
5. **Modeling** *(inferred)*

   * Train regression models (e.g., linear regression, random forest) to predict HCHO emissions.
   * Evaluate models using metrics such as RMSE, MAE, and R².
6. **Visualization & Insights**

   * Compare predicted vs actual values; optionally visualize spatial distribution using geopy-derived coordinates.

### **Reproducing the Notebook**

* Clone the repo:

```bash
git clone https://github.com/Starlight0901/HCHO-Emission-Prediction-for-Sri-Lanka
```

* Open in **Google Colab** or locally in **Jupyter Notebook**.
* Ensure required libraries are installed:

```bash
pip install pandas scikit-learn matplotlib seaborn geopy
```

* Mount Google Drive (for Colab) and place CSVs in the expected paths or update paths in the notebook.
