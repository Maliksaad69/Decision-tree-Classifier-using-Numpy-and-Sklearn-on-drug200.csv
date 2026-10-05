# 🩺 Decision Tree Classifier for Drug Recommendation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Project Overview
A machine learning implementation of a **Decision Tree Classifier** to predict patient drug prescriptions based on clinical metrics (Age, Sex, BP, Cholesterol, and Na-to-K ratio). Includes both a custom NumPy decision tree implementation from scratch and Scikit-Learn benchmarking.

## ✨ Key Features
- **Custom Decision Tree Engine**: Information Gain, Entropy computation, and tree recursion implemented using NumPy.
- **Scikit-Learn Benchmarking**: Comparative analysis against `sklearn.tree.DecisionTreeClassifier`.
- **EDA & Data Processing**: Categorical label encoding and feature distribution visualizations using Seaborn and Matplotlib.
- **Model Evaluation**: Confusion matrices, accuracy calculations, and visual tree structure outputs.

## 🛠️ Tech Stack
| Category | Technology |
| :--- | :--- |
| **Language** | Python 3.x |
| **Libraries** | NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook |

## 📁 Project Structure
```text
├── README.md
├── decision tree.ipynb
└── drug200.csv
```

## ⚙️ Installation & Usage
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook "Decision tree Classifier.ipynb"
```

## 👤 Author
Developed as part of my ML portfolio.
