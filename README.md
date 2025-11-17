# OnlineRetail_FraudDetection4

![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![GitHub last commit](https://img.shields.io/github/last-commit/AlaaTouihri/OnlineRetail_FraudDetection)


##  Description
Projet de détection de fraude basé sur le dataset *Online Retail*. L'objectif est d'identifier les transactions suspectes en appliquant des techniques d'analyse de données et de machine learning. Le projet inclut le nettoyage des données, l'exploration, le feature engineering et la mise en place de modèles de détection d'anomalies.

---

##  Objectifs
- Identifier les transactions frauduleuses dans un dataset e-commerce.  
- Explorer les données et visualiser les tendances et anomalies.  
- Construire des features pertinentes pour la détection de fraude.  
- Appliquer des modèles de machine learning pour détecter les comportements suspects.  
- Générer des insights exploitables pour renforcer la sécurité des opérations.

---

## 🗂 Structure du projet

OnlineRetail_FraudDetection/
│
├─ data/ # Dataset utilisé
│ └─ Online_Retail.csv
│
├─ notebooks/ # Notebooks d'analyse
│ └─ OnlineRetail_FraudDetection.ipynb
│
├─ reports/ # Rapports et visualisations
│ └─ figures/
│ ├─ Distribution des montants des transactions.png
│ ├─ Top 10 pays par nombre de transactions.png
│ ├─ Top 10 produits vendus.png
│ ├─ Transactions suspectes détectées par Isolation Forest.png
│ └─ Évolution des ventes par mois.png
│
└─ README.md # Ce fichier

---

## 🛠 Technologies utilisées
- Python 3.x  
- Pandas, NumPy (traitement des données)  
- Matplotlib, Seaborn (visualisations)  
- Scikit-learn (machine learning, détection d’anomalies)  
- Jupyter Notebook  

---

##  Instructions pour reproduire le projet
1. Cloner le repository :  
```bash
git clone https://github.com/AlaaTouihri/OnlineRetail_FraudDetection.git
git clone https://github.com/AlaaTouihri/OnlineRetail_FraudDetection.git
Installer les dépendances (si nécessaire) :

bash
Copier le code
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
Ouvrir le notebook dans Jupyter :

bash
Copier le code
jupyter notebook notebooks/OnlineRetail_FraudDetection.ipynb
Suivre l’analyse étape par étape dans le notebook.

Résultats
Visualisation de la distribution des montants de transactions.

Classement des top produits et pays par nombre de transactions.

Identification des transactions suspectes via Isolation Forest.

Suivi de l’évolution des ventes par mois.

🔗 Lien du projet
OnlineRetail_FraudDetection sur GitHub

