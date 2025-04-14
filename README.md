
# 🎯 Sonar Rock vs Mine Classifier

This machine learning project classifies sonar signals as either **rocks** or **mines** using various classification algorithms and enhanced analysis techniques. It's based on the classic UCI Sonar Dataset, enriched with model comparisons, feature importance visualization, and robustness testing.

---

## 📂 Dataset

- **Name:** Sonar, Mines vs. Rocks
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs+rocks))
- **Description:** Each sample contains 60 numeric features representing the energy of sonar signals bounced off surfaces. The target label indicates whether the object was a rock (`R`) or a mine (`M`).

---

## 🧠 Models Used

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**

Each model is trained and evaluated on a stratified train/test split to ensure balanced label distribution.

---

## 📊 Key Features

✅ Basic Data Analysis  
✅ Model Training and Comparison  
✅ Accuracy Evaluation  
✅ Confusion Matrix + Classification Report  
✅ Feature Importance Plot (Random Forest)  
✅ Noise Robustness Testing  
✅ Single-Sample Prediction Example  

---

## 🖼️ Visualizations

### 📈 Model Accuracy Comparison
Bar plot showing the accuracy of each model.

### 📉 Confusion Matrix
Confusion matrix of the best-performing model.

### 📌 Feature Importances
Top 15 features contributing to classification (when using Random Forest).

---

## 🧪 Example Prediction

```python
input_data = (
    0.0307, 0.0523, 0.0653, 0.0521, 0.0611, 0.0577, 0.0665, 0.0664, 0.1460, 0.2792,
    ... # truncated for clarity
)
```

The model predicts whether the sonar signal reflects off a **rock** or a **mine**.

---

## ⚙️ Installation & Usage

1. Clone this repository:
```bash
git clone https://github.com/your-username/sonar-rock-vs-mine.git
cd sonar-rock-vs-mine
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the main script:
```bash
python sonar_rock_vs_mine.py
```

---

## 📁 Requirements

- Python 3.7+
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`

You can install them all via:
```bash
pip install -r requirements.txt
```

---

## 🧠 Advanced Feature Ideas

Here are some future upgrades that can take this project even further:

- 🌐 Web interface using Streamlit or Gradio  
- 🔍 SHAP explainability for feature contribution analysis  
- 🔁 K-fold cross-validation  
- 🤖 AutoML (TPOT or AutoSklearn integration)  
- 🛡️ Anomaly detection & adversarial sample handling  

---

## 📬 Contact

Made with ❤️ by [Your Name]  
📧 Email: your.email@example.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile)

---

## 📜 License

This project is licensed under the MIT License.
