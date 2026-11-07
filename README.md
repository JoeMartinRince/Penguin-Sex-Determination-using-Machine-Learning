# 🐧 Penguin Sex Classification with Machine Learning  

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)  
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn)](https://scikit-learn.org/stable/)  
[![Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab)](https://colab.research.google.com/)  

---


## 📖 Overview  
This project predicts the **sex of penguins** using machine learning and the **Palmer Penguins dataset**.  
Traditional DNA-based methods are invasive 🧬 — so here we build a **non-invasive, data-driven pipeline** using physical traits like:  

- 🧭 Culmen Length & Depth  
- 🐦 Flipper Length  
- ⚖️ Body Mass   

By comparing multiple ML models, we identify the best approach for ecological research and conservation. 🌍  

---


## 📊 Dataset  
📌 **Palmer Penguins Dataset** → [link](https://allisonhorst.github.io/palmerpenguins/)  
- Species: Adélie, Chinstrap, Gentoo  
- Features used:  
  - `culmen_length_mm`  
  - `culmen_depth_mm`  
  - `flipper_length_mm`  
  - `body_mass_g`  
- Target: **Sex** (Male / Female)  

---

## ⚙️ Methodology  
1. **Preprocessing**  
   - Handle missing values  
   - Encode target labels (Male → 0, Female → 1)  
   - Normalize with StandardScaler  
   - Train/test split (80/20)  

2. **Models Tested**  
   - 🔹 Logistic Regression  
   - 🔹 Support Vector Machine (SVM)  
   - 🔹 Random Forest Classifier  

3. **Evaluation Metrics**  
   - Accuracy ✅  
   - Precision / Recall / F1-score  
   - Confusion Matrix  
   - Feature Importance  

---


## 🚀 Results  
✨ **Best Model:** Random Forest Classifier → **96% accuracy**  

| Model                | Accuracy |
|-----------------------|----------|
| Logistic Regression   | 90%      |
| Support Vector Machine| 92%      |
| Random Forest         | 96% 🏆   |

🔑 **Key Insight** → Flipper length & body mass are the strongest predictors.  

---
