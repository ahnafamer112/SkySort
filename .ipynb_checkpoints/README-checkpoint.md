# SkySort 🌌  
**Machine learning classifier for stars, quasars, and galaxies using Sloan Digital Sky Survey (SDSS) data.**

## 📖 Overview
SkySort is an astronomy data science project that applies machine learning to classify celestial objects — specifically **stars**, **quasars**, and **galaxies** — based on photometric data from the **Sloan Digital Sky Survey (SDSS)**.  

The goal is to demonstrate how modern data analysis and ML techniques can be applied in astrophysics for automated classification, aiding large-scale astronomical surveys.

---

## 🚀 Features
- **Data acquisition** from SDSS public datasets.  
- **Data preprocessing** and feature engineering.  
- Multiple ML models tested: Logistic Regression, Random Forest, XGBoost, etc.  
- Performance evaluation with accuracy, F1-score, and confusion matrices.  
- Interactive Jupyter Notebook visualizations.  

---

## 📂 Project Structure
SkySort/
│
├── data/
│   └── .gitkeep
├── notebooks/
│   └── .gitkeep
├── src/
│   └── .gitkeep
├── images/
│   └── .gitkeep
├── requirements.txt
├── LICENSE
├── .gitignore
└── README.md


---

## 📊 Dataset
**Source:** Sloan Digital Sky Survey (SDSS) — DR16 or later  
**Access:** [https://skyserver.sdss.org/](https://skyserver.sdss.org/)  
**Sample size:** ~100k objects (balanced among stars, quasars, galaxies)  

---

## 🛠 Technologies Used
- **Python 3.9+**  
- **Jupyter Lab** for analysis  
- **NumPy, Pandas** for data processing  
- **Matplotlib, Seaborn** for plotting  
- **Scikit-learn** for ML models  
- **Astropy** for astronomy utilities  

---

## 📈 Example Results
_Example confusion matrix and feature importance plots will go here once the model is trained._  
![Example Plot](images/confusion_matrix.png)  

---

## 📌 Installation & Usage
1. **Clone the repository**:
```bash
git clone https://github.com/YOUR_USERNAME/SkySort.git
cd SkySort
