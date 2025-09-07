# ❤️ CardioPredict  

> ❤ CardioPredict – Heart Disease Prediction using Machine Learning   
> 🧠 A supervised (Classification) machine learning project for predicting **heart disease** using patient health data.     
 
--- 
     
## 📌 Overview   
CardioPredict is a **supervised classification ML project** built to predict whether a patient has heart disease based on clinical attributes such as age, sex, cholesterol level, blood pressure, etc.  
  
The project demonstrates the **end-to-end ML workflow**:  
- 📊 Data preprocessing     
- 🔍 Exploratory Data Analysis (EDA)    
- 🤖 Model training & evaluation   
- ✅ Performance comparison across algorithms  

---

## 🧩 Problem Definition  
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?  

---

## 📂 Dataset  
- **Source 1:** [UCI Machine Learning Repository – Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
- **Source 2:** [Kaggle – Heart Disease Classification Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)  

The dataset includes features like:  
- `age` → Age in years  
- `sex` → Gender (1 = male, 0 = female)  
- `cp` → Chest pain type (0 = typical angina, 1 = atypical, 2 = non-anginal, 3 = asymptomatic)  
- `trestbps` → Resting blood pressure (mm Hg)  
- `chol` → Serum cholesterol (mg/dl)  
- `fbs` → Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)  
- *(and many more clinical features)*  

---

## 🎯 Project Goals  
- 🏥 Assist in **early detection of heart disease**  
- ⚡ Evaluate multiple ML algorithms (Logistic Regression, Random Forest, etc.)  
- 📈 Achieve high accuracy (>95%) as proof of concept  

---

## 🛠️ Tech Stack  
- **Programming:** Python 🐍  
- **Libraries:**  
  - `pandas`, `numpy` → Data handling  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → ML models & evaluation  

---

## 🚀 Project Workflow  
1. **Data Collection** → Load dataset from Kaggle/UCI  
2. **Exploratory Data Analysis (EDA)** → Visualization of patterns & correlations  
3. **Feature Engineering** → Handle missing values, encode categorical features  
4. **Model Building** → Train classifiers (Logistic Regression, Random Forest, etc.)  
5. **Model Evaluation** → Accuracy, Precision, Recall, F1-score, ROC-AUC  
6. **Experimentation** → Compare models & tune hyperparameters  

---

## 📊 Results & Insights  
- ✅ Logistic Regression achieved **high interpretability**  
- 🌳 Random Forest & Ensemble Models gave **better overall accuracy**  
- 📈 Achieved close to **95% accuracy** on test data  

*(You can add graphs/metrics screenshots here later)*  

---

## 📦 Installation & Usage  

### 🔹 Step 1: Clone the repository  

git clone https://github.com/<your-username>/CardioPredict.git
cd CardioPredict

### 🔹 Step 2: Create conda environment
conda env create --prefix ./env -f ../../project_environment.yml
conda activate ./env

### 🔹 Step 3: Run Jupyter Notebook
jupyter notebook

---

## 📜 Future Improvements
- Add Deep Learning models (Neural Networks)
- Deploy via Flask/Django web app
- Build an interactive dashboard for predictions

---

### 🧑‍💻 Author 
- 👨‍🎓 Om Sonawane
- 💼 Computer Engineering Student | Full-stack & ML Developer
- 🌐 Passionate about AI, ML, and UI/UX
- 📫 Connect with me on LinkedIn (https://www.linkedin.com/in/om-sonawane360/)

