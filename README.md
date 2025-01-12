# Prédictions climatiques pour soutenir l'agriculture dans la région d'Hanoi 🌱

## 📖 Introduction
Ce projet utilise des techniques avancées de **deep learning**, notamment les réseaux LSTM (Long Short-Term Memory), pour analyser et prédire les variables climatiques comme la température. L'objectif est de fournir des prévisions climatiques précises, permettant une meilleure gestion des ressources agricoles et une anticipation des variations climatiques dans la région d'Hanoi.

---
# 🌍 Prédictions climatiques pour l'agriculture dans la région d'Hanoi

**Objectif principal** : Fournir des prévisions climatiques précises pour améliorer la gestion des ressources agricoles dans la région d'Hanoi, grâce à l'application de techniques de deep learning.

---

## 🚀 Résumé du projet

Ce projet met en œuvre un modèle de deep learning basé sur des réseaux de neurones **LSTM** (Long Short-Term Memory), spécialement adaptés aux séries temporelles, pour analyser et prédire des variables climatiques importantes telles que la température. L'objectif est d'aider les agriculteurs et les décideurs à mieux planifier leurs activités agricoles face aux variations climatiques.

- **Type de données analysées** : Données climatiques historiques (température, humidité, etc.).
- **Approche utilisée** : Réseaux LSTM combinés avec des techniques de régularisation pour éviter le surapprentissage.
- **Impact attendu** : Une meilleure gestion agricole, une anticipation des changements climatiques et une réduction des risques liés aux conditions météorologiques.

---

## 📊 Résultats principaux

### Courbes de performance du modèle

**Évolution de la perte et de l'erreur absolue moyenne (MAE)** pendant l'entraînement et la validation.

![Courbes de perte et MAE](./path_to_images/loss_mae_curves.png)

---

### Comparaison des valeurs réelles et des prédictions

Une comparaison directe entre les **valeurs réelles** et les **prédictions du modèle**, démontrant une forte corrélation.

![Comparaison valeurs réelles vs prédictions](./path_to_images/real_vs_pred_comparison.png)

---

### Graphe de dispersion

Un graphique montrant la **relation linéaire** entre les valeurs réelles et les prédictions.

![Graphe de dispersion](./path_to_images/scatter_plot.png)

---

## 🎯 Objectifs détaillés

1. **Prédire avec précision les variables climatiques** pour une meilleure planification agricole.
2. **Exploiter les données historiques** pour capturer les tendances climatiques à long terme.
3. **Utiliser un modèle LSTM performant**, connu pour sa capacité à gérer les dépendances temporelles.
4. **Évaluer les performances du modèle** avec des métriques comme le MSE, MAE et R².

---

## 🔧 Outils et technologies

- **Langage de programmation** : Python 3.8+
- **Framework** : TensorFlow/Keras
- **Bibliothèques utilisées** :
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - TensorFlow

---

## 🗂️ Structure du projet

