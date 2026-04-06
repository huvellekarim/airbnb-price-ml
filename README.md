# Prédiction des prix Airbnb à Paris
## Objectif
Ce projet vise à analyser les facteurs influençant les prix des logements Airbnb à Paris et à développer un modèle de machine learning capable de prédire le prix moyen journalier.
## Données
Les données utilisées couvrent trois périodes :

- Septembre 2024
- Décembre 2024
- Mars 2025

Après nettoyage, les datasets ont été fusionnés et enrichis avec des variables temporelles.
## Feature engineering
- Calcul de la distance au centre de Paris
- Calcul de la distance à la Seine
- Ajout de la variable période
- Encodage des variables catégorielles (quartier, période)
## Analyse
L’analyse montre que la localisation joue un rôle majeur dans la formation des prix, notamment :

- proximité de la Seine
- proximité du centre
- disparités entre quartiers
## Modèles utilisés
### Régression linéaire
- R² ≈ 0.11
- RMSE ≈ 100€
### Random Forest
- R² ≈ 0.38
- RMSE ≈ 82€
Le modèle Random Forest améliore significativement la performance en capturant des relations non linéaires.
## Résultats
Les variables les plus importantes sont :

- distance à la Seine
- distance au centre
- disponibilité du logement

La localisation apparaît comme le facteur déterminant.
## Limites
- absence de variables qualitatives (équipements, standing)
- complexité du marché difficile à modéliser
## Améliorations possibles
- ajout de nouvelles variables
- optimisation des modèles
- création d’un dashboard
## Technologies utilisées
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
## Fichier principal
Airbnb_ml.ipynb
