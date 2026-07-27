# 🌾 AI-Powered Crop Yield Prediction and Optimization

Predicting crop yield and recommending the right crop for the right field — powered by machine learning on real agricultural data.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-ML%20Models-F7931E?logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

Agriculture depends on countless variables that shift from field to field and season to season — rainfall, temperature, humidity, soil composition, and fertilizer inputs all interact in ways that are hard to judge by intuition alone. This project applies **supervised machine learning** to that problem, using historical agronomic data to predict optimal crop outcomes and recommend suitable crops based on environmental and soil conditions.

The goal is simple: help move farming decisions from guesswork to **data-driven insight**, so farmers and agri-planners can boost productivity, use resources more efficiently, and farm more sustainably. 🌍

---

## ✨ Key Features

- 📊 **Exploratory data analysis** of the crop recommendation dataset — distributions, correlations, and feature relationships
- 🧪 **Feature engineering** across rainfall, temperature, humidity, soil pH, and NPK (Nitrogen, Phosphorus, Potassium) values
- 🤖 **Multiple ML models trained and benchmarked** using Scikit-learn to find the best-performing classifier/regressor
- 📈 **Model evaluation** with accuracy metrics, confusion matrices, and performance visualizations
- 🌱 **Crop recommendation output** tailored to the input environmental conditions
- 🔁 **Dedicated testing notebook** to validate the trained model separately from development

---

## ⚙️ Tech Stack

| Category | Tools |
|---|---|
| **Language** | Python 🐍 |
| **Data Handling** | Pandas, NumPy |
| **Modeling** | Scikit-learn |
| **Visualization** | Matplotlib |
| **Environment** | Jupyter Notebook |
| **Data Storage** | CSV (`Crop_recommendation.csv`) |

---

## 📂 Project Structure

```
AI-Crop-Yield-Production/
├── Crop recommendation.ipynb                  # Main notebook — data prep, EDA & model training
├── Crop_Recommendation_Testing_Final.ipynb    # Testing & evaluation notebook
├── Crop_recommendation.csv                    # Dataset (rainfall, temperature, soil, NPK, humidity, etc.)
└── README.md                                  # Project documentation
```

---

## 🚀 How It Works

1. **Load & explore** the agricultural dataset with Pandas, checking for nulls, outliers, and feature distributions.
2. **Preprocess** the data — encode categorical features, scale numerical values, and split into train/test sets.
3. **Train models** using Scikit-learn algorithms and compare performance across them.
4. **Evaluate** using accuracy scores and other classification metrics, then visualize results with Matplotlib.
5. **Test independently** in `Crop_Recommendation_Testing_Final.ipynb` to validate the model on unseen inputs.
6. **Generate predictions** — output the recommended crop or expected yield for a given set of environmental inputs.

---

## 🖥️ Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```

### Run it
```bash
git clone https://github.com/chitram-hp/AI-Crop-Yield-Production.git
cd AI-Crop-Yield-Production
jupyter notebook "Crop recommendation.ipynb"
```

---

## 📊 Example Outputs

- Crop-wise prediction/recommendation results
- Correlation heatmaps between rainfall, fertilizer (NPK), and yield
- Model accuracy comparisons across algorithms
- Feature importance visualizations

---

## 🏆 Highlights

- Built an end-to-end ML pipeline — from raw agricultural data to actionable crop recommendations
- Improved model accuracy through targeted feature engineering
- Validated results with a dedicated, separate testing notebook for reliability
- Designed with sustainability in mind — recommending efficient resource use over guesswork

---

## 🔭 Future Work

- 🌐 **Deploy as a web app** (Flask/Streamlit) so farmers can input conditions and get instant recommendations through a simple UI
- 📱 **Mobile-first interface** for on-field use in low-connectivity rural areas
- 🛰️ **Integrate real-time weather and satellite data** (via APIs) instead of relying solely on static historical CSV data
- 🧠 **Upgrade to deep learning models** (e.g., neural networks) to capture more complex, non-linear relationships in the data
- 🗺️ **Add geospatial/regional analysis** to tailor recommendations by district or soil zone
- 🧪 **Expand the fertilizer optimization module** to recommend precise NPK dosages, not just crop choice
- 📦 **Package as a reusable API** so the model can plug into larger agri-tech platforms
- 🔄 **Continuous learning pipeline** to retrain the model as new seasonal data becomes available
- 📉 **Add yield-quantity regression** (not just crop-type classification) for more granular production forecasts
- 🌦️ **Climate-change scenario modeling** to test how shifting weather patterns could affect future yields

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repo and submit a pull request.

## 📄 License

This project is available under the MIT License.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
