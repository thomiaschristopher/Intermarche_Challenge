# Intermarche_Challenge

Lien de la compétition :
https://challenge.datafactory-intermarche.fr/fr/challenge/1/details#tab_ranking

## Resume
Prédiction des volumes de ventes des produits de grande consommation  Ce challenge consiste à fournir un modèle prédictif permettant d’estimer les volumes de ventes journaliers réalisés par différents points de vente pour divers produits de grande consommation (hors produits frais ou à poids variable).

## Approche :
Après plusieurs tests j'ai préféré m'orienter vers le modèle "LGBM : Light Gradient Boosting Machine" - Regressor. qui était plus rapide à exécuter que le XGBOOST pour environ les mêmes résultats.

![Challenge Intermarche_1](https://user-images.githubusercontent.com/64421607/124708069-fdba4c80-def9-11eb-90eb-a4974aa15014.png)
![Challenge Intermarche](https://user-images.githubusercontent.com/64421607/124708077-001ca680-defa-11eb-9835-b004f19475f5.png)

# Problème rencontré : 
Le principale problème que j'ai rencontré était évidement la gestion de la mémoire pour exploiter ce gros dataset.
J'ai éssayé d'échantilloner le dataset pour exploter un maximum de données sur 16 GB.

## Conclusion :
Ceci était ma première compétition officielle, ainsi que ma première approche d'un problème de Time series.
Etant débutant sur les sujets IA/Data Science je me suis mis comme objectif de produire au moins une solution et de l'améliorer jusqu'à la deadline.
Même si je pense que ma démarche n'est pas forcément correct j'ai pris énormément de plaisir à réaliser cette compétion.

![Capture Intermarche](https://user-images.githubusercontent.com/64421607/124708406-86d18380-defa-11eb-949b-0430040a8f2c.JPG)



