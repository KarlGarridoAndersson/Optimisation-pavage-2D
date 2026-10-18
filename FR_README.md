# Optimisation discrète de la compacité géométrique : Pavage 2D

Ce dépôt contient les travaux de recherche et l'implémentation algorithmique liés à l'étude sur l'assemblage automatique de blocs connexes (polyominos).

## Résumé de la recherche
Ce projet s'attaque à la complexité **NP-complète** du problème de pavage. L'objectif est de maximiser la compacité d'un assemblage sur une grille discrète en utilisant des approches heuristiques basées sur la topologie des sommets.

### Heuristiques développées
* **H1 (Approche Gloutonne)** : Sélection et placement basés sur l'ordre maximal des sommets.
* **H2 (Adaptation Structurelle)** : Utilisation d'une métrique d'ajustement entre sommets pour optimiser l'emboîtement.
* **H3 (Référentiel Local)** : Algorithme de force brute locale servant de base de comparaison pour évaluer la performance des solutions.

## Indicateurs de Performance
Le succès des algorithmes est mesuré via :
1. **L'indice de compacité** : Analyse du rapport aire/périmètre de l'enveloppe.
2. **La ressemblance morphologique** : Comparaison avec les configurations théoriques optimales.

## Organisation du dépôt
* `/Notebook` : Code source de la logique de fusion et des calculs heuristiques.
* `/article` : Texte intégral de la publication détaillant le modèle mathématique.
* `/guide utilisation` : Guide pour appréhender les différentes variables introduites dans le notebook. 
