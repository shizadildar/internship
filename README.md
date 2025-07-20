# Task 1: Exploring and Visualizing a Simple Dataset

## 📊 Objective
This project aims to demonstrate how to load, summarize, and visualize a simple dataset using Python. The Iris dataset is used for this task.

---

## 📁 Dataset
We use the famous **Iris Dataset**, which contains measurements of iris flowers from three different species: *Setosa*, *Versicolor*, and *Virginica*. It includes the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (Target)

This dataset is available through the `seaborn` library or can be downloaded in CSV format.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- Seaborn
- Matplotlib

---

## 🔍 Instructions & Code Overview

### 1️⃣ Load Dataset
```python
import pandas as pd
import seaborn as sns

# Load Iris dataset from seaborn
df = sns.load_dataset('iris')
