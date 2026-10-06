# ML Lab 05: Multilayer Perceptron (MLP) Neural Networks

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/pandas-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-013243.svg?logo=numpy&logoColor=white)](https://numpy.org/)

---

## Academic Details
- **Student Name:** Shrri Dharshan D R
- **Register Number:** 23BPS1090
- **Course Code:** BCSE209P
- **Course Title:** Machine Learning Laboratory
- **Faculty:** Dr. S. Shridevi
- **Institution:** School of Computer Science and Engineering (SCOPE), VIT Chennai

---

## Overview
This repository contains comprehensive laboratory implementations of **Multilayer Perceptron (MLP)** Feedforward Artificial Neural Networks across five benchmark classification problems from the UCI Machine Learning Repository.

The laboratory explores deep neural network principles including forward propagation, non-linear activation functions (ReLU, Logistic, Tanh, Softmax), categorical cross-entropy loss formulation, error backpropagation via gradient descent (Adam optimizer), weight regularization (L2 penalty / $\alpha$), and hyperparameter tuning of hidden layer topologies.

---

## Experiments & Datasets

### 1. Dry Bean Multi-Class Classification
- **Dataset:** Dry Bean Dataset ([UCI ID: 602](https://archive.ics.uci.edu/dataset/602))
- **Objective:** Classify dry beans into 7 distinct commercial varieties (Seker, Barbunya, Bombay, Cali, Dermosan, Horoz, Sira) using 16 computer vision geometric shape measurements.
- **Notebook:** [23BPS1090_ShrriDharshan_ML_Lab_MLP_DryBean.ipynb](./23BPS1090_ShrriDharshan_ML_Lab_MLP_DryBean.ipynb)
- **Data Directory:** `dry_bean_data/`

### 2. Mushroom Edibility Classification
- **Dataset:** Mushroom (Agaricus-Lepiota) Dataset ([UCI ID: 73](https://archive.ics.uci.edu/dataset/73))
- **Objective:** Classify mushroom specimens as safely **edible** (`e`) or **poisonous** (`p`) based on 22 categorical macroscopic physical traits.
- **Notebook:** [23BPS1090_ShrriDharshan_ML_Lab_MLP_Mushroom.ipynb](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Mushroom.ipynb)
- **Data Directory:** `mushroom_data/`

### 3. Rice Grain Variety Classification
- **Dataset:** Rice (Cammeo and Osmancik) Dataset ([UCI ID: 545](https://archive.ics.uci.edu/dataset/545))
- **Objective:** Discriminate between **Cammeo** and **Osmancik** rice varieties using 7 morphological image features.
- **Notebook:** [23BPS1090_ShrriDharshan_ML_Lab_MLP_Rice.ipynb](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Rice.ipynb)
- **Data Directory:** `rice_data/`

### 4. Wheat Kernel Seeds Classification
- **Dataset:** Seeds Dataset ([UCI ID: 236](https://archive.ics.uci.edu/dataset/236))
- **Objective:** Classify wheat grains into 3 cultivar varieties (**Kama**, **Rosa**, **Canadian**) based on internal kernel X-ray structure measurements.
- **Notebook:** [23BPS1090_ShrriDharshan_ML_Lab_MLP_Seeds.ipynb](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Seeds.ipynb)
- **Data Directory:** `seeds_data/`

### 5. Wine Cultivar Origin Recognition
- **Dataset:** Wine Dataset ([UCI ID: 109](https://archive.ics.uci.edu/dataset/109))
- **Objective:** Identify the geographical origin of Italian wines (3 cultivars) using 13 chemical and constituent concentrations.
- **Notebook:** [23BPS1090_ShrriDharshan_ML_Lab_MLP_Wine.ipynb](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Wine.ipynb)
- **Data Directory:** `wine_data/`

---

## Evaluation Metrics
- **Multi-Class Accuracy & Balanced Accuracy**
- **Precision, Recall, and F1-Score** (Macro and Weighted averages)
- **Multi-Class Confusion Matrices**
- **Training Loss Curves:** Tracking loss minimization and convergence across training epochs
- **Multi-Class ROC-AUC Curves** (One-vs-Rest / OvR)

---

## Repository Structure
```text
ML-Lab-05-Multilayer-Perceptron-MLP/
├── 23BPS1090_ShrriDharshan_ML_Lab_MLP_DryBean.ipynb
├── 23BPS1090_ShrriDharshan_ML_Lab_MLP_Mushroom.ipynb
├── 23BPS1090_ShrriDharshan_ML_Lab_MLP_Rice.ipynb
├── 23BPS1090_ShrriDharshan_ML_Lab_MLP_Seeds.ipynb
├── 23BPS1090_ShrriDharshan_ML_Lab_MLP_Wine.ipynb
├── dry_bean_data/
├── mushroom_data/
├── rice_data/
├── seeds_data/
├── wine_data/
├── .gitignore
└── README.md
```

---

## How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/shrridharshan27/ML-Lab-05-Multilayer-Perceptron-MLP.git
   cd ML-Lab-05-Multilayer-Perceptron-MLP
   ```
2. **Install dependencies:**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn ucimlrepo scipy jupyter
   ```
3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
