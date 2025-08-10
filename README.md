
# 📊 Portfolio Actuariat – Makemissa Ouedraogo

Bienvenue sur mon portfolio !  
Vous trouverez ici mes projets académiques et personnels en actuariat, modélisation financière et data science.

---

## 📌 Projet 1 : Modélisation des taux d’intérêt – Modèle de Vasicek

**🎯 Objectif :**  
Calibration et simulation des taux courts via le modèle d’Ornstein-Uhlenbeck (Vasicek à un facteur).  

**🛠 Outils :**  
R, VBA/Excel, statistiques appliquées

**📂 Contenu :**
- Rapport PDF : ![`projet_modèle_de_Vasicek_massvie_perso.pdf`](https://github.com/Makemissa/Portfolio-Actuariat/blob/main/projet_mod%C3%A8le_de_Vasicek_massvie%20perso.pdf)
- Données Excel : ![`Nouvelle_courbe_650_periodes123.xlsm`](https://github.com/Makemissa/Portfolio-Actuariat/blob/main/Nouvelle%20courbe%20650%20pA%CC%83%C2%A9riodes123.xlsm)
- Code R et VBA inclus dans le rapport

**📊 Résultats visuels :**
- Comparaison des taux observés et extrapolés  
  ![Taux observés vs extrapolés](https://github.com/Makemissa/Portfolio-Actuariat/blob/main/Taux%20vs%20Simulation.png)

- Simulation Monte Carlo  
  ![Simulation Monte Carlo](https://github.com/Makemissa/Portfolio-Actuariat/blob/main/Simulation%20Monte%20Carlo.png)

- Illustration du retour à la moyenne  
  ![Retour à la moyenne](https://github.com/Makemissa/Portfolio-Actuariat/blob/main/Courbe%20Simulation.png)

**📈 Conclusion :**
Le modèle de Vasicek respecte la tendance générale des taux observés mais lisse les variations extrêmes.  
Il est simple et robuste mais présente des limites face aux pics de volatilité.

---

## 📌 Projet 2 : Prediction avec Python

# 🚗 Prédiction des prix de voitures – Projet Data Science

Ce projet vise à prédire le prix de vente de voitures d'occasion à partir de leurs caractéristiques techniques et commerciales (marque, année, kilométrage, etc.).

Réalisé en **Python**, ce projet suit une approche complète de Data Science : nettoyage des données, analyse exploratoire, modélisation et évaluation.

# 🎯 Objectifs
- Nettoyer et préparer un jeu de données brutes issues de GitHub.
- Analyser les relations entre variables explicatives et prix.
- Entraîner et comparer plusieurs modèles de régression.
- Évaluer les performances avec RMSE et R².

# 📂 Données
- **Source** : [Dataset GitHub](lien_vers_dataset)
- **Taille** : ... lignes × ... colonnes
- **Variables principales** :
  - `make` : marque
  - `model` : modèle
  - `year` : année
  - `mileage` : kilométrage
  - `price` : prix (cible à prédire)
  - `engine volume`, `doors`, `airbags`, etc.

---

# 🛠 Méthodologie
1. **Nettoyage des données**
   - Conversion des variables au bon type (ex. `Levy`, `Mileage`)
   - Correction des formats incohérents (`Doors`, `Engine volume`)
   - Gestion des valeurs manquantes et suppression des outliers
2. **Analyse exploratoire**
   - Statistiques descriptives
   - Détection d'asymétries (skewness) et transformation éventuelle
   - Visualisations (corrélations, distributions)
3. **Modélisation**
   - Régression Linéaire
   - Lasso Regression
   - Ridge Regression
   - KNN Regressor
4. **Évaluation**
   - Validation croisée
   - Calcul de RMSE et R² sur jeu de test

---

## 📊 Résultats

| Modèle              | R² (CV) | R² (Test) | RMSE (CV) | RMSE (Test) |
|---------------------|---------|-----------|-----------|-------------|
| Régression Linéaire | ...     | ...       | ...       | ...         |
| Lasso               | ...     | ...       | ...       | ...         |
| Ridge               | ...     | ...       | ...       | ...         |
| KNN                 | ...     | ...       | ...       | ...         |

---

## 📷 Visualisations
- Importance des variables :  
  ![Feature Importance](feature_importance.png)
- Prédictions vs Observations :  
  ![Predictions vs Observations](pred_vs_obs.png)

---



📫 **Contact :**
- LinkedIn : [Votre profil LinkedIn](https://linkedin.com)
- Email : makemissaouedraos@gmail.com
