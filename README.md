
# 🚴‍♀️ Bike Demand Prediction Using Machine Learning 🚴‍♂️  
> Forecasting daily bike rentals based on weather, time, and seasonal features with ML models.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-blue?logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-teal?logo=seaborn)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-red?logo=streamlit)

---

## 📌 Project Overview

🚲 This project predicts the **number of bike rentals per day** using historical data including temperature, weather, season, holidays, and more.  
Built as part of a Data Science internship training to apply real-world ML practices — from preprocessing to model tuning & evaluation.

### 📄 Screenshot PDF

[View the output plot (PDF)](screenshots/%22screenshot%20-%20Copy.pdf%22)

---

## 📸 Screenshot – Output Example

<div align="center">
  <img src="https://github.com/Reshmakhaan/Bike_Demand_prediction/screenshot - Copy.pdf" width="600" alt="Prediction Output">
</div>

---

## 🧠 ML Models Used

- 🔹 Linear Regression
- 🔹 Ridge & Lasso Regression
- 🔹 Random Forest Regressor ✅ *(Best Performer)*
- 🔹 Gradient Boosting (optional for extension)

---

## 💡 Features Used

| Feature Name     | Description                        |
|------------------|-------------------------------------|
| `season`         | Spring, Summer, Fall, Winter       |
| `temp`           | Normalized temperature (°C)        |
| `humidity`       | Humidity percentage                |
| `windspeed`      | Normalized wind speed              |
| `holiday`        | Is it a holiday (1/0)?             |
| `workingday`     | Is it a working day (1/0)?         |
| `datetime`       | Extracted into day, hour, month    |

---

## 🔍 Exploratory Data Analysis (EDA)

- 📊 Correlation heatmaps
- 📅 Hourly demand trends
- 🌡️ Weather vs rental patterns
- 🔍 Outlier handling & scaling

---

## 📈 Results

| Model               | RMSE     | R² Score |
|--------------------|----------|----------|
| Linear Regression  | 912.45   | 0.57     |
| Ridge Regression   | 880.21   | 0.61     |
| **Random Forest**  | **802.33** | **0.71** ✅ |

✔️ Random Forest model achieved **highest accuracy** and lowest error.

---

## 🧰 Tech Stack

| Tool             | Purpose                    |
|------------------|-----------------------------|
| 🐍 Python        | Core programming language   |
| 📦 Pandas        | Data manipulation           |
| 🔢 NumPy         | Numerical computations      |
| 📉 Scikit-learn  | Machine Learning models     |
| 📊 Matplotlib    | Visualization               |
| 🌈 Seaborn       | Advanced EDA plots          |
| 📈 Streamlit     | Web dashboard deployment    |

---

## 🧪 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/Reshmakhaan/Bike_Demand_prediction.git
cd Bike_Demand_prediction

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the notebook or scripts
jupyter notebook notebooks/Bike_Prediction.ipynb
````

---

## 🧾 Folder Structure

```
Bike_Demand_prediction/
│
├── data/                 # Dataset CSV files
├── notebooks/            # Jupyter Notebooks
├── src/                  # Python scripts (cleaning, modeling)
├── outputs/              # Generated plots & saved models
├── screenshots/          # Project output images
├── requirements.txt      # Project dependencies
└── README.md             # This file
```

---

## 📦 Future Scope

* ✅ Model Deployment with Streamlit
* 📉 Advanced Time Series Model (LSTM)
* 🔄 Real-time prediction API with FastAPI
* 📍 Geo-location data for station-wise predictions

---

## 🤝 Acknowledgments

Thanks to:

* [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)
* Internship program at **AICTE Eduskills**
* Mentors & peer reviewers who helped fine-tune the solution

---

## 👩‍💻 Author

**Reshma Patan**
📧 Email: [reshmapatan@gmail.com](mailto:reshmapatan@example.com)
🔗 [LinkedIn](https://www.linkedin.com/in/reshmapatan/)

---

> Give this project a ⭐ if it helped you!
> *Ride the data wave 🚴‍♂️, predict smarter 💡.*

```

---



### 🧑‍💻 Contributors

* **Reshma Patan** – initial work & analysis
* 
### 📧 Contact
Created by **\[RESHMA]** – feel free to reach out!
📧 Email: [reshmapatan915@gmail.com](mailto:your.email@example.com)

---

*Happy forecasting! 🎉🚲*

---

### Customize this with:

* Replace placeholders (e.g. model metrics, your name, screenshots).
* Embed actual `.png` screenshots in the "Screenshots" section.
* Replace tool icons with actual SVG or Emoji versions:

