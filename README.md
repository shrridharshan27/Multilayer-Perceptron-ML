# Multilayer Perceptron (MLP) Artificial Neural Networks

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E.svg?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/pandas-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-013243.svg?logo=numpy&logoColor=white)](https://numpy.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Author
- **Shrri Dharshan D R** — [@shrridharshan27](https://github.com/shrridharshan27)

---

## Overview
This repository contains deep neural network implementations of **Multilayer Perceptron (MLP)** Feedforward Artificial Neural Networks evaluated across five classification benchmark domains from the UCI Machine Learning Repository.

The project evaluates forward propagation mathematics, non-linear activation functions (ReLU, Sigmoid, Tanh, Softmax), categorical cross-entropy loss formulation, error backpropagation with Adam stochastic gradient descent, weight regularization (L2 penalty $\alpha$), and hidden layer architectural designs.

---

## Project Modules & Datasets

### 1. Dry Bean Multi-Class Variety Classification
- **Dataset:** Dry Bean Dataset ([UCI ID: 602](https://archive.ics.uci.edu/dataset/602))
- **Objective:** Classify dry beans into 7 commercial varieties using 16 computer vision geometric shape features.
- **Notebook:** [`23BPS1090_ShrriDharshan_ML_Lab_MLP_DryBean.ipynb`](./23BPS1090_ShrriDharshan_ML_Lab_MLP_DryBean.ipynb)
- **Data Directory:** `dry_bean_data/`

### 2. Mushroom Edibility Classification
- **Dataset:** Mushroom (Agaricus-Lepiota) Dataset ([UCI ID: 73](https://archive.ics.uci.edu/dataset/73))
- **Objective:** Classify mushrooms as **edible** (`e`) or **poisonous** (`p`) from 22 categorical macroscopic physical traits.
- **Notebook:** [`23BPS1090_ShrriDharshan_ML_Lab_MLP_Mushroom.ipynb`](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Mushroom.ipynb)
- **Data Directory:** `mushroom_data/`

### 3. Rice Grain Variety Classification
- **Dataset:** Rice (Cammeo and Osmancik) Dataset ([UCI ID: 545](https://archive.ics.uci.edu/dataset/545))
- **Objective:** Discriminate between **Cammeo** and **Osmancik** rice varieties using 7 geometric morphological features.
- **Notebook:** [`23BPS1090_ShrriDharshan_ML_Lab_MLP_Rice.ipynb`](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Rice.ipynb)
- **Data Directory:** `rice_data/`

### 4. Wheat Kernel Seeds Classification
- **Dataset:** Seeds Dataset ([UCI ID: 236](https://archive.ics.uci.edu/dataset/236))
- **Objective:** Classify wheat grains into 3 cultivar varieties (**Kama**, **Rosa**, **Canadian**) from internal kernel X-ray measurements.
- **Notebook:** [`23BPS1090_ShrriDharshan_ML_Lab_MLP_Seeds.ipynb`](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Seeds.ipynb)
- **Data Directory:** `seeds_data/`

### 5. Wine Cultivar Origin Recognition
- **Dataset:** Wine Dataset ([UCI ID: 109](https://archive.ics.uci.edu/dataset/109))
- **Objective:** Identify the geographic cultivar origin of Italian wines using 13 chemical constituent concentrations.
- **Notebook:** [`23BPS1090_ShrriDharshan_ML_Lab_MLP_Wine.ipynb`](./23BPS1090_ShrriDharshan_ML_Lab_MLP_Wine.ipynb)
- **Data Directory:** `wine_data/`

---

## Evaluation Metrics
- **Multi-Class Accuracy & Balanced Accuracy**
- **Precision, Recall, and F1-Score** (Macro and Weighted averages)
- **Multi-Class Confusion Matrices**
- **Loss Convergence Curves:** Tracking training epoch loss decay
- **Multi-Class ROC-AUC Curves** (One-vs-Rest)

---

## Project Structure
```text
Multilayer-Perceptron-ML/
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

## Quickstart & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/shrridharshan27/Multilayer-Perceptron-ML.git
   cd Multilayer-Perceptron-ML
   ```
2. **Install requirements:**
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn ucimlrepo scipy jupyter
   ```
3. **Run the notebooks:**
   ```bash
   jupyter notebook
   ```

---

## License
Distributed under the [MIT License](https://opensource.org/licenses/MIT).
