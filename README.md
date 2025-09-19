# PyFeat Auto Feature Engineering 🚀

An interactive **Streamlit web app** that automates data preprocessing and feature selection for Machine Learning workflows.  
This project helps users quickly prepare datasets by handling missing values, encoding categorical features, and selecting the most relevant features using statistical methods.

---

## 📖 Introduction
Feature engineering is one of the most time-consuming steps in the Machine Learning pipeline.  
This project simplifies the process by providing a **no-code interface** where users can upload CSV files and automatically:  

- Inspect and clean data (remove duplicates, handle missing values).  
- Encode categorical features using Label Encoding.  
- Apply multiple feature selection techniques like **Chi-Square, ANOVA, Correlation, Mutual Information, and Variance Threshold**.  
- Download the cleaned and feature-selected dataset for ML model building.  

---

## ✨ Features
- 📂 Upload CSV files directly.  
- 🧹 Automatic preprocessing: missing value imputation, duplicate removal, label encoding.  
- 📊 Multiple feature selection methods:  
  - Chi-Square Test  
  - ANOVA (f_classif)  
  - Correlation Coefficient  
  - Mutual Information  
  - Variance Threshold  
- ⬇️ Download transformed dataset in one click.  
- 🔍 Interactive UI built with **Streamlit**.  

---

## ⚙️ Installation (Run Locally)

Follow these steps to set up and run the project locally:  

### 1️⃣ Clone the repository
```bash
git clone https://github.com/vishald018/PyFeat-Auto-Feature-Engineering-Tool.git
cd PyFeat-Auto-Feature-Engineering-Tool
```
### 2️⃣ Create virtual environment
```bash
python -m venv myenv

# Activate (Windows)
myenv\Scripts\activate

# Activate (Linux/Mac)
source myenv/bin/activate
```
### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Streamlit app
```
streamlit run app.py
```

### Enjoy doing automated Feature Engineering with PyFeat

