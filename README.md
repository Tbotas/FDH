# Machine learning B3A
### Arnaud Daugen / Anthony Flores / Théo Hay / Théo Ferreira

## Introduction 

L'objectif de ce TP est la découverte du Machine Learning à travers un excercice d'estimation des prix de vente de maison. Nous avons pour cela utilisé les outils que Kaggle a mis à notre disposition.

L'énoncé est le suivant:  
 A l'aide d'un fichier "train" regroupant les différentes caractéristiques de plusieurs maisons différentes dont le prix est donné, nous allons devoir étudier les différentes corrélation entre les caractéristiques des maisons et leur prix. L'exercice final sera de réussir à "prédire" le prix des nouvelles maisons du fichier "test" en fonction de leurs caratéristiques.

Nous pouvons découper nos travaux en quatre grands "chapitres":

1. **Compréhention** du problème
2. **Visualisation** des données
3. **Traitement** des données
4. **Prédiction** du résultat

Vous trouverez ci-dessous le tableau relatif aux différentes versions de notre notebook et des scores que nous avons obtenus.

# Historique des mises à jour
| Version | Modifications | Score | Notes
|-|-|-|-|
| 1|/| 0.35513 | Modèle basique, traitement simple des données  |
| 2.1 | Nouveau Modèle | 0.35218 | Utilisation de Cross Validation pour déterminer les meilleurs paramètres pour le nouveau modèle (RandomForest) |
| 2.2 | Nouveau traitement de données | 0.16127 | Séléction des colonnes à prendre en compte en fonction de leur corrélation avec les prix de vente|
| 2.3 | Nouvelle conf du modèle | 0.16107 | Nouveau paramètres de Cross Validation pour de nouveaux paramètres pour le modèle |
| 2.3bis | Utilisation de XGBoost comme modèle | 0.16616 | Le nouveau modèle est moins efficace, les hyper paramètres peuvent en être la cause, ainsi que le nombre de colonnes qui peut être insuffisant. |
