# 🌸 Iris Flower — Exploratory Data Analysis (EDA)

> 🇹🇷 [Türkçe README için tıklayın](./README.md)

This project performs a basic Exploratory Data Analysis (EDA) on the classic **Iris** dataset. The data is examined, visualized, and the relationships between species are explored using Pandas, Seaborn, and Matplotlib. A K-Nearest Neighbors classifier is also trained to validate the patterns found during EDA.

---

## 📊 Contents

| Step | Description |
|------|-------------|
| Data Loading | `bezdekIris.data` is read with pandas, column names are assigned |
| Exploration | Data profiling with `shape`, `describe`, `info`, `isnull` |
| Visualization | Pairplot, Boxplot, Correlation Heatmap |
| Model Training | KNN classifier with train/test split and confusion matrix |

---

## 🗂️ Dataset

The classic Iris dataset from the UCI Machine Learning Repository is used.

**Features:**

- `sepal_length` — Sepal length (cm)
- `sepal_width` — Sepal width (cm)
- `petal_length` — Petal length (cm)
- `petal_width` — Petal width (cm)
- `species` — Flower species: *Iris-setosa*, *Iris-versicolor*, *Iris-virginica*

Download the dataset: [UCI Iris Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/bezdekIris.data)

---

## 🚀 Setup & Usage

### Requirements

```
Python 3.8+
pandas
seaborn
matplotlib
scikit-learn
jupyter
```

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/elifyesilyurt/iris.git
cd iris

# 2. Install dependencies
pip install -r requirements.txt

# 3. Download the dataset and place bezdekIris.data in the project folder

# 4. Open the notebook
jupyter notebook iris.ipynb
```

---

## 📈 Visualizations

### Pairplot — All Feature Relationships
Pairwise scatter plots colored by species

### Boxplot — Petal Length Distribution
The difference between species is most apparent in `petal_length`

### Heatmap — Correlation Matrix
Strong positive correlation (~0.96) between `petal_length` and `petal_width`

### Confusion Matrix — KNN Results
Visualizes model prediction accuracy across all three species

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-4C72B0)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-F7931E?logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 📁 Project Structure

```
iris/
├── iris.ipynb          # Main notebook
├── bezdekIris.data     # Dataset (download manually)
├── requirements.txt    # Python dependencies
├── README.md           # Turkish README
└── README_EN.md        # This file
```

---

## 📝 License

MIT License
