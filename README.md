# 🛳️ Titanic Data Exploration

This notebook explores the Titanic dataset provided by the Seaborn library. It focuses on basic data understanding, cleaning, and visualization using Pandas, Seaborn, and Matplotlib.

---

## 📦 Dataset

The dataset contains passenger information from the Titanic ship, including:

- Demographics (age, sex, class)
- Ticket fare and embarkation port
- Survival status

Dataset is loaded directly from `seaborn.load_dataset("titanic")`.

---

## 📊 Libraries Used

- **Pandas** – for data manipulation
- **Seaborn** – for visualizations and loading the dataset
- **Matplotlib** – for plot rendering

---

## 🔍 What’s Inside

- View of dataset structure and missing values
- Survival distribution overall and by gender
- Age distribution histogram
- Fare vs Age scatter plot colored by passenger class
- Passenger class breakdown by port of embarkation

---

## 📎 How to Run

1. Clone this repo or download the `.ipynb` file.
2. Open the notebook in **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.
3. Run the cells step by step.

> Make sure you have `seaborn`, `pandas`, and `matplotlib` installed.

```bash
pip install seaborn pandas matplotlib
