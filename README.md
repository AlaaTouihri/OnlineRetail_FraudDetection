# OnlineRetail Fraud Detection

Ce projet consiste à analyser un dataset e-commerce et à construire un modèle de **détection de transactions frauduleuses**. Il s'agit d'un projet complet incluant préparation des données, analyse exploratoire, modélisation et visualisations.

---

## 📌 Objectif du projet

Développer un pipeline de data science permettant de :

* Comprendre la structure du dataset Online Retail.
* Nettoyer et préparer les données pour l'analyse.
* Concevoir des features pertinentes comme `TotalPrice`.
* Construire un modèle de classification pour prédire les transactions frauduleuses.
* Évaluer les performances du modèle et analyser les résultats.

---

## 📂 Structure du projet

```
OnlineRetail_FraudDetection/
│
├─ data/                    # Dataset original et données nettoyées
├─ notebooks/               # Notebook Jupyter contenant toute l'analyse
├─ scripts/                 # (Optionnel) Scripts Python si pipeline séparé
├─ reports/
│   └─ figures/             # Graphiques générés (matrice confusion, etc.)
└─ README.md
```

---

## 🧪 Contenu du notebook

Le fichier principal du projet est :

```
notebooks/fraud_detection.ipynb
```

Il contient :

* 📊 **Exploration des données** (EDA)
* 🧹 **Nettoyage du dataset**
* ⚙️ **Feature engineering**
* 🤖 **Modélisation** (Random Forest ou autre)
* 📈 **Évaluation du modèle** :

  * Matrice de confusion
  * Accuracy, Recall, Precision
  * Courbe ROC (si appliqué)

Les graphiques générés sont exportés dans :

```
reports/figures/
```

---

## 🛠️ Installation et exécution

### 1. Cloner le projet

```bash
git clone https://github.com/USERNAME/OnlineRetail_FraudDetection.git
cd OnlineRetail_FraudDetection
```

### 2. Installer les dépendances

```bash
pip install -r requirements.txt
```

(Si tu veux, je peux te générer le fichier `requirements.txt`.)

### 3. Ouvrir le notebook

```bash
jupyter notebook notebooks/fraud_detection.ipynb
```

---

## 📘 Dataset

Le dataset utilisé provient de :

* **Online Retail Dataset (UCI Machine Learning Repository)**

Il contient :

* Numéro de facture
* Produit
* Quantité
* Prix unitaire
* Pays
* Identifiant client

---

## 🧠 Modèle utilisé

Un modèle de classification basé sur :

* **RandomForestClassifier**

Pourquoi ?

* Performant
* Robuste au bruit
* Gère bien les variables numériques

---

## 📊 Résultats

Les principaux résultats obtenus :

* **Matrice de confusion** (exportée dans `reports/figures/`)
* **Métriques complètes** via `classification_report`

---

## 🚀 Améliorations possibles

* Optimisation des hyperparamètres (GridSearch / RandomSearch)
* Ajout de nouvelles features
* Tests avec d'autres modèles (XGBoost, SVM...)
* Mise en place d'un tableau de bord (Streamlit / Dash)

---

## 👤 Auteur

**Alaa Touihri**
Data Analyst | Machine Learning | Python | SQL
LinkedIn : [https://www.linkedin.com/in/alaa-touihri-a03a96122](https://www.linkedin.com/in/alaa-touihri-a03a96122)

---

## 📄 Licence

Ce projet est libre d'utilisation pour le travail académique et la démonstration professionnelle.
