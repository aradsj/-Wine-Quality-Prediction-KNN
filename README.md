
---

## ۳. Wine-Quality-Prediction-KNN

```markdown
# 🍷 Wine-Quality-Prediction-KNN

A Machine Learning project implementing a **K-Nearest Neighbors (KNN) Regressor** model to predict the quality score of red wine based on 11 physico-chemical input features.

---

## ✨ ML Details

* **Regression Modeling:** Utilizes `KNeighborsRegressor` to predict a continuous quality score.
* **Data Preprocessing:**
    * Data loading with a semicolon (`;`) delimiter.
    * Feature scaling using **StandardScaler** for optimal distance-based algorithm performance.
    * Standard `train_test_split` procedure.
* **Evaluation:** Model performance is assessed using standard regression metrics.

---

## 🛠️ Technologies Used

| Technology | Role |
| :--- | :--- |
| **Python** | Core language. |
| **Jupyter Notebook** | Environment for model training and evaluation. |
| **Pandas / NumPy** | Data manipulation and numerical arrays. |
| **Scikit-learn** | Implementing **KNeighborsRegressor**, **StandardScaler**, and model selection utilities. |

---

## 🚀 Getting Started

### Prerequisites
* Python 3.x
* Pip

### Installation

```bash
pip install pandas numpy scikit-learn jupyter
Execution
Clone the repository:

Bash

git clone [https://github.com/YOUR_USERNAME/Wine-Quality-Prediction-KNN.git](https://github.com/YOUR_USERNAME/Wine-Quality-Prediction-KNN.git)
cd Wine-Quality-Prediction-KNN
Run the Notebook:

Bash

jupyter notebook wine_quality.ipynb
📂 File Structure
wine_quality.ipynb: Jupyter Notebook with the complete ML pipeline.

wine_quality.csv: The Red Wine Quality dataset.
