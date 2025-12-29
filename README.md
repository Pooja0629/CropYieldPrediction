
#  Crop Yield Prediction Using Machine Learning

An AI-driven agricultural analytics system that predicts crop yield based on historical farming data and market indicators. The project helps farmers, researchers, and policymakers make data-driven decisions to improve agricultural productivity and resource planning.

---

##  Features

###  Core Functionality

* **Crop Yield Prediction**

  * Predicts crop yield using historical agricultural data
  * Uses a Random Forest Regression model for accurate predictions

* **Data Preprocessing & Cleaning**

  * Handles missing values and feature scaling
  * Encodes categorical variables such as crop type and season

* **Model Evaluation**

  * Performance measured using:

    * RMSE (Root Mean Squared Error)
    * R² Score (Coefficient of Determination)

* **Visualization & Analytics**

  * Actual vs Predicted Yield comparison
  * Feature importance analysis
  * Statistical insights into agricultural factors

---

##  Market & Environmental Indicators

* Integrates **state-level market indicators** (min, max, modal prices)
* Analyzes impact of:

  * Rainfall
  * Fertilizer usage
  * Pesticide usage
  * Cultivation area
* Soil data analyzed independently for future integration

---

##  Machine Learning Workflow

1. Dataset Collection (Crop Yield & Market Data)
2. Data Cleaning & Feature Engineering
3. Train-Test Split
4. Model Training (Random Forest)
5. Model Evaluation
6. Visualization & Result Interpretation
7. Model Saving for Deployment

---

##  Technology Stack

###  Backend / ML

* **Python 3.8+**
* **Pandas & NumPy** – Data processing
* **scikit-learn** – Machine learning models
* **Matplotlib & Seaborn** – Data visualization
* **Joblib** – Model persistence

---

##  Model Performance

* **R² Score:** ~0.98
* **RMSE:** Low error indicating strong predictive performance

> Minor deviation between actual and predicted values reflects realistic real-world conditions and avoids overfitting.

---

##  Dataset

* **Crop Yield Dataset**

  * Crop
  * Crop Year
  * Season
  * State
  * Area
  * Rainfall
  * Fertilizer
  * Pesticide
  * Yield

* **Market Indicators Dataset**

  * State-wise agricultural pricing data

 Soil nutrient data analyzed separately due to spatial granularity limitations.

---

##  Visual Outputs

* Actual vs Predicted Crop Yield Graph
* Feature Importance Bar Chart
* Statistical Distribution Plots

---

##  How It Works

1. User provides historical crop data
2. Model learns patterns from agricultural and market indicators
3. Trained model predicts expected crop yield
4. Results are visualized and evaluated for accuracy

---

##  Future Enhancements

* Integration of real-time weather APIs
* District-level soil data mapping
* Deep learning models (LSTM for time-series yield prediction)
* Web interface using Flask or Streamlit
* Farmer-friendly mobile dashboard

---

##  Installation

```bash
git clone https://github.com/Pooja0629/CropYieldPrediction
cd CropYieldPrediction
pip install -r requirements.txt
```

---

##  Usage

```bash
python crop_yield_prediction.py
```

Or run the Jupyter Notebook:

```bash
jupyter notebook
```

---

##  License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---

##  Acknowledgments

* Kaggle for agricultural datasets
* scikit-learn for machine learning tools
* Open-source community for continuous support

---

##  Contact

**Author:** Pooja S
 Email: [poojashree2266@gmail.com](mailto:poojashree2266@gmail.com)
 GitHub: [Pooja0629](https://github.com/Pooja0629)

---

##  Project Links

* **Repository:** [https://github.com/Pooja0629/CropYieldPrediction](https://github.com/Pooja0629/CropYieldPrediction)
* **Issues:** [https://github.com/Pooja0629/CropYieldPrediction/issues](https://github.com/Pooja0629/CropYieldPrediction/issues)

---

Empowering agriculture with data-driven insights for smarter and sustainable crop yield decisions.
