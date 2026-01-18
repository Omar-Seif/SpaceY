# 🚀 SpaceX Launch Analysis & Prediction

## 📌 Overview
This project analyzes SpaceX launch data to uncover insights into launch success trends, site performance, payload capacity, and mission outcomes. Using Python and machine learning, the project includes **exploratory data analysis, visualization, and predictive modeling** to classify successful vs. failed launches.

---

## 🛠️ Skills & Tools Applied
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Folium
- **Data Cleaning & Wrangling**: Handling missing values, feature engineering
- **Exploratory Data Analysis (EDA)**: Statistical summaries, correlation analysis, distribution plots
- **Data Visualization**: Interactive maps, bar charts, scatter plots, geospatial plotting
- **Machine Learning**: Scikit-learn, Logistic Regression, SVM, Decision Trees, KNN, model evaluation
- **Deployment**: Jupyter Notebooks, GitHub, Markdown documentation

---

## 📂 Project Structure
SpaceX-Launch-Analysis/
├── data/ # Raw and cleaned datasets
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── scripts/ # Python scripts for automation
├── visuals/ # Charts, maps, and plots
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## 🔍 Key Analyses Performed

### 1. **Launch Site Comparison**
- **Flight Frequency**: CCSFS SLC 40 had the most launches (~80), followed by KSC LC 39A (~40–60), then VAFB SLC 4E (~20).
- **Payload Capacity**: KSC LC 39A handles the heaviest payloads (up to 15,000+ mass units).

### 2. **Payload vs. Success Trends**
- Lighter payloads were more frequent across all sites.
- Heavier payloads were concentrated at KSC LC 39A.

### 3. **Geospatial Visualization**
- Created an interactive Folium map showing launch sites across the US, Gulf, and Caribbean.
- Color-coded markers indicate launch success/failure.

### 4. **Machine Learning Model**
- Built and compared four classification models:
  - Logistic Regression
  - SVM
  - Decision Tree
  - KNN
- **Best Model**: Logistic Regression & SVM tied with **83.33% test accuracy**.

---

## 📊 Results & Insights
- **Most Active Site**: CCSFS SLC 40 (high-cadence, medium-lift missions).
- **Heaviest Payloads**: KSC LC 39A (supports crewed and heavy-lift missions).
- **Best Predictive Model**: Logistic Regression demonstrated strong generalization for launch success prediction.

---

## 🚀 How to Run This Project

### 1. Clone the Repository
```bash
git clone https://github.com/Omar-Seif/SpaceY.git
```

### 2. Install dependencies

# Core Data Science Libraries
pandas>=1.3.0
numpy>=1.21.0
scipy>=1.7.0

# Data Visualization
matplotlib>=3.4.0
seaborn>=0.11.0
plotly>=5.3.0
folium>=0.12.0

# Machine Learning & Statistics
scikit-learn>=0.24.0
statsmodels>=0.12.0

# Jupyter & Interactive Computing
jupyter>=1.0.0
ipykernel>=6.0.0
ipywidgets>=7.6.0

# Web Scraping & APIs (if used)
requests>=2.26.0
beautifulsoup4>=4.9.0

---

## 👨‍💻 Author
Omar Farahat
https://www.linkedin.com/in/omar-farahat-313987277/
