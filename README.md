# K-Means Clustering on CIA Country Facts Dataset

A machine learning project that applies K-Means Clustering to group countries based on socioeconomic, demographic, and economic indicators from the CIA Country Facts dataset.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Missing Value Handling
- Feature Scaling using StandardScaler
- K-Means Clustering
- Elbow Method for Optimal Cluster Selection
- Cluster Analysis and Interpretation
- Correlation Analysis
- Interactive World Map Visualization using Plotly
- Exploratory Data Analysis (EDA)

---

## 📖 Overview

This project uses the K-Means Clustering algorithm, an unsupervised machine learning technique, to identify patterns among countries based on various indicators such as population, GDP, literacy rate, birth rate, industry contribution, and technological development.

The goal is to discover hidden relationships and automatically group countries with similar characteristics without using predefined labels.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Plotly
- Jupyter Notebook

---

## 📂 Project Structure

```text
KMeans-Country-Clustering/
│
├── Kmeans-Clustering-Project-Solution.ipynb
├── CIA_Country_Facts.csv
├── country_iso_codes.csv
├── README.md
├── requirements.txt
└── images/
```

---

## 📊 Dataset

### Source
CIA Country Facts Dataset

### Dataset Information

The dataset contains country-level statistics including:

- Population
- GDP Per Capita
- Literacy Rate
- Birth Rate
- Death Rate
- Climate
- Agriculture
- Industry
- Service Sector
- Net Migration
- Phones per 1000 People
- Region

### Objective

Group countries into clusters based on their socioeconomic and demographic similarities.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/rivu-intel45/KMeans-Country-Clustering.git

cd KMeans-Country-Clustering
```

Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

Or:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Kmeans-Clustering-Project-Solution.ipynb
```

Run all cells sequentially to reproduce the analysis.

---

## 📈 Methodology

### 1. Data Preprocessing

- Removed unnecessary columns
- Handled missing values
- Encoded categorical variables
- Standardized features using StandardScaler

### 2. Exploratory Data Analysis

- Distribution Analysis
- Correlation Heatmaps
- Cluster Maps
- Scatter Plots

### 3. K-Means Clustering

Applied K-Means clustering on standardized features to identify groups of similar countries.

### 4. Elbow Method

Used Sum of Squared Distances (SSD) to determine the optimal number of clusters.

### 5. Cluster Interpretation

Analyzed cluster characteristics based on:

- Economic Development
- Literacy Rates
- Population Metrics
- Technology Adoption
- Geographic Factors

### 6. Geographic Visualization

Displayed cluster assignments on an interactive world map using Plotly Choropleth Maps.

---

## 📷 Results

### Key Findings

- Countries with similar economic and demographic characteristics were successfully grouped together.
- Developed and developing nations formed distinct clusters.
- Literacy, GDP, and technology access emerged as strong clustering indicators.
- Geographic visualization provided intuitive insights into global development patterns.

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Unsupervised Machine Learning
- K-Means Clustering
- Feature Engineering
- Data Cleaning
- Missing Value Imputation
- Feature Scaling
- Exploratory Data Analysis
- Data Visualization
- Geographic Data Mapping

---

## 🔮 Future Improvements

- Implement DBSCAN Clustering
- Compare with Hierarchical Clustering
- Add Silhouette Score Evaluation
- Develop an Interactive Dashboard
- Deploy as a Web Application

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to your branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Protyay Saha**

GitHub: https://github.com/rivu-intel45
