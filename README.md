# E-Commerce Sales Analysis

Analyse des ventes du dataset Olist (Brazilian E-Commerce) avec Python, Pandas et Plotly.

**Dataset :** Kaggle, "Brazilian E-Commerce Public Dataset by Olist" (commandes livrées, janvier 2017 à août 2018).

## Indicateurs clés

| Indicateur | Valeur |
|---|---|
| Revenu total | 13 179 778 BRL |
| Commandes | 96 203 |
| Clients uniques | 93 096 |
| Panier moyen | 137,00 BRL |
| Clients récurrents | 3,0 % |

Le revenu correspond à la somme des prix des articles, hors frais de livraison.

## Questions analysées

1. Comment le revenu évolue-t-il dans le temps ?
2. Quelles catégories de produits génèrent le plus de revenu ?
3. Quels États brésiliens achètent le plus ?
4. Les retards de livraison influencent-ils les avis clients ?

## Principaux constats

- Seulement 3 % des clients commandent plus d'une fois : la fidélisation est très faible.
- (À compléter avec ce que tu observes sur chaque graphique)

## Outils

Python, Pandas, NumPy, Plotly, Jupyter

## Lancer le projet

1. Télécharger le dataset sur Kaggle et placer les fichiers CSV dans un dossier `data/`.
2. Installer les dépendances : `pip install pandas numpy plotly jupyter`
3. Ouvrir `notebooks/analysis.ipynb` et exécuter les cellules dans l'ordre.