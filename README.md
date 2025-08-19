# 🏡 Boston Housing ML Regression

This project demonstrates **Machine Learning Regression Models** using the **Boston Housing dataset**.  
We compare **Linear Regression**, **Ridge**, **Lasso**, and **ElasticNet**, evaluating them with **Train-Test Split**, **K-Fold Cross Validation**, and **cross_val_score**.

---

## 📌 Features
- Apply **Linear Regression, Ridge, Lasso, ElasticNet**  
- Evaluate with:
  - Root Mean Squared Error (RMSE)  
  - K-Fold Cross Validation  
  - cross_val_score (with negative MSE scoring)  
- Compare coefficients across models  

---

## 📂 Project Structure
```

boston-housing-ml-regression/
│── MLO-Boston-Housing-Regression-Models-Kfold-Lasso-Elastic-Ridge.ipynb  # Main notebook with models and evaluation
│── data/
│    └── Boston.CSV       # Dataset file
│── requirements.txt      # Dependencies
│── README.md             # Documentation

````

---

## ⚙️ Installation

```bash
# Clone repository
git clone https://github.com/vipunsanjana/boston-housing-regression-models-kfold-lasso-elastic-ridge.git
cd boston-housing-regression-models-kfold-lasso-elastic-ridge

# Install dependencies
pip install -r requirements.txt
````

---

## 🚀 Usage

Open the Jupyter Notebook to run and explore the models:

```bash
# Launch Jupyter Notebook
jupyter notebook

# Then open:
MLO-Boston-Housing-Regression-Models-Kfold-Lasso-Elastic-Ridge.ipynb
```

Run the cells to train and evaluate the models, view RMSEs, K-Fold results, and coefficient comparisons.

---

## 📊 Example Output

```
Linear Regression RMSE: 5.12
Ridge Regression RMSE: 5.05
Lasso Regression RMSE: 5.47
ElasticNet RMSE: 5.33

K-Fold RMSEs: [4.9, 5.2, 5.1, 5.0, 5.3]
Cross-Val RMSEs: [5.0, 5.1, 5.2, ...]
```

---

## 📚 Learnings

* **Ridge** reduces overfitting with coefficient shrinkage
* **Lasso** can eliminate irrelevant features (coefficients = 0)
* **ElasticNet** combines Ridge and Lasso benefits

---

## 🛠️ Tech Stack

* Python 3.x
* pandas, numpy
* scikit-learn

---

## 👨‍💻 Author

**Vipun Sanjana**

*Software Engineer | Full Stack | ML & DevOps*

---
