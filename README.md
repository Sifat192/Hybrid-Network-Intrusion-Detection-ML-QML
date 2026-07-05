# Hybrid Network Intrusion Detection using Classical and Quantum Machine Learning

A hybrid cybersecurity project that develops an end-to-end **Network Intrusion Detection System (NIDS)** by integrating **Classical Machine Learning** and **Quantum Machine Learning (QML)** techniques. The project preprocesses network traffic data, engineers relevant features, applies dimensionality reduction, and compares the performance of classical classifiers with a **Quantum Support Vector Classifier (QSVC)** implemented using **Qiskit**.

---

## Project Workflow

```text
Dataset Collection
        │
        ▼
Data Integration
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Feature Engineering
        │
        ▼
Feature Scaling
        │
        ▼
Classical Machine Learning
(Random Forest, Logistic Regression, SVM)
        │
        ├──────────────┐
        ▼              ▼
Feature Selection     PCA
        │              │
        └──────┬───────┘
               ▼
      Quantum Feature Map
               │
               ▼
    Quantum Kernel (Qiskit)
               │
               ▼
             QSVC
               │
               ▼
 Performance Evaluation & Comparison
```

---

## Features

- Network traffic dataset integration from multiple CSV files
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Binary attack classification
- Feature engineering
- Feature scaling using StandardScaler
- Feature selection using Random Forest importance
- Dimensionality reduction using PCA
- Classical Machine Learning models:
  - Random Forest
  - Logistic Regression
  - Support Vector Machine (SVM)
- Quantum Machine Learning using:
  - Qiskit
  - Quantum Feature Maps
  - Fidelity Quantum Kernel
  - Quantum Support Vector Classifier (QSVC)
- Comparative performance evaluation between Classical ML and Quantum ML

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Qiskit
- Qiskit Machine Learning

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Hybrid-Network-Intrusion-Detection.git
cd Hybrid-Network-Intrusion-Detection
```

### Install dependencies

Using pip:

```bash
pip install -r requirements.txt
```

Or recreate the Conda environment:

```bash
conda env create -f environment.yml
conda activate quantum
```

---

## Results

This project evaluates and compares multiple **Classical Machine Learning** models with a **Quantum Support Vector Classifier (QSVC)** using standard classification metrics, demonstrating the potential of Quantum Machine Learning for cybersecurity applications.

---

## Future Improvements

- Evaluate on larger and more diverse intrusion detection datasets.
- Train and evaluate on real IBM Quantum hardware.
- Investigate hybrid quantum-classical learning architectures.
- Experiment with additional quantum feature maps and kernels.
- Optimize quantum circuits for improved scalability and execution efficiency.

---

## Author

**Sifat Bhatia**

B.Tech Computer Science Engineering

Interests:
- Artificial Intelligence
- Quantum Machine Learning
- Cybersecurity
- Data Science
