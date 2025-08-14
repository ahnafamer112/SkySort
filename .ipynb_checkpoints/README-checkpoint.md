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

## 📅 Roadmap
- [ ] Acquire SDSS dataset and preprocess
- [ ] Train initial models (Logistic Regression, Random Forest)
- [ ] Tune hyperparameters
- [ ] Add neural network classifier
- [ ] Upload example visualizations and final results

---

## 📜 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## ✨ Author
**Ahnaf Amer Adit**  
Astronomy & Data Science Enthusiast 🌠  
GitHub: [https://github.com/ahnafamer112](https://github.com/ahnafamer112)

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

git clone https://github.com/ahnafamer112/SkySort.git
cd SkySort

2. python3 -m venv venv

3. source venv/bin/activate

4. pip install -r requirements.txt

5. jupyter lab