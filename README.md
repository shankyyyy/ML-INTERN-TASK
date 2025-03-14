# **Machine Learning Intern Task - Hyperspectral Imaging**

## **Project Overview**
This project involves processing **hyperspectral imaging data** to predict **mycotoxin (DON) concentration** in corn samples. The pipeline includes **data preprocessing, dimensionality reduction (PCA), machine learning model training (Random Forest & Neural Network), and model evaluation.**

## **Repository Structure**
```
📂 ML-Intern-Task
├── 📄 ML_Intern_Task.ipynb   # Jupyter Notebook with complete code
├── 📄 REPORT.md              # Summary of methodology and findings
├── 📄 README.md              # Setup instructions & project details
└── 📂 data/
    ├── TASK-ML-INTERN.csv    # Dataset (not included in GitHub)
```

## **Installation & Setup**
### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/ML-Intern-Task.git
cd ML-Intern-Task
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
> If `requirements.txt` is not provided, install manually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```

### **3. Run the Jupyter Notebook**
```bash
jupyter notebook ML_Intern_Task.ipynb
```

## **How to Use**
- Run all cells in `ML_Intern_Task.ipynb` to preprocess data, train models, and evaluate performance.
- Check `REPORT.md` for insights into the results.

## **Key Features**
✅ **Min-Max Scaling for normalization**  
✅ **PCA for feature reduction**  
✅ **Random Forest & Neural Network for regression**  
✅ **GridSearchCV for hyperparameter tuning**  
✅ **Evaluation metrics: MAE, RMSE, R² Score**  

---
🚀 **Developed as part of the ML Intern Task for Hyperspectral Imaging Analysis.**

