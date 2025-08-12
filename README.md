# Mortgage Loan Approval Prediction

## 📌 Overview
This project predicts whether a mortgage loan application will be **approved (1)** or **rejected (0)** based on applicant data.  
It uses statistical analysis, preprocessing pipelines, and multiple classification algorithms to build and compare predictive models.

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
- **Techniques:** Data cleaning, PCA, Logistic Regression, KNN, Random Forest, MLP  
- **Evaluation:** Cross-validation, ROC curves, AUC score

---

## 📂 Project Structure

---

## 🔍 Steps & Methodology
1. **Data Preprocessing**
   - Handled missing values and outliers
   - Encoded categorical variables using one-hot encoding
   - Normalized numerical features

2. **Dimensionality Reduction**
   - Applied PCA to reduce dimensionality while retaining >95% variance

3. **Model Training**
   - Trained and compared Logistic Regression, KNN, Random Forest, and MLP
   - Tuned hyperparameters via GridSearchCV

4. **Evaluation**
   - Used 5-fold cross-validation for reliability
   - Plotted ROC curves and calculated AUC scores
   - Compared performance across models

---

## 📊 Results
| Model               | Accuracy  | ROC AUC |
|---------------------|-----------|---------|
| Logistic Regression | 0.783     | 0.865     |
| KNN                 | 0.744     | 0.806     |
| Random Forest       | 0.773     | 0.851     |
| MLP                 | **0.790** | **0.868** |

---

## 📈 Visualizations
- Correlation heatmap of features:
- 
<img width="1129" height="886" alt="image" src="https://github.com/user-attachments/assets/5653add2-0345-46e3-8a76-b6f9548be597" />

- ROC curves for all models:

<img width="1632" height="498" alt="image" src="https://github.com/user-attachments/assets/3fb62567-c89f-4369-9fd9-1e626360ce51" />

- Confusion matrix for best-performing model (MLP):
- 
<img width="524" height="455" alt="image" src="https://github.com/user-attachments/assets/4a76351c-5225-40a7-8943-90057b4f3898" />


---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/Savin97/Mortgage-Loan-Approval-Prediction.git
cd Mortgage-Loan-Approval-Prediction
```

2. (Optional) Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the notebook:
```bash
jupyter notebook notebooks/Mortgage Loan Approval Prediction Model.ipynb
```
