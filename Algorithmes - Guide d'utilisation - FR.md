# Guide d'Utilisation : Algorithmes d'Assemblage

Ce guide détaille le fonctionnement technique et la manipulation des variables pour l'optimisation de la compacité géométrique.

## Configuration de l'Instance

Le pilotage de l'algorithme s'effectue via le dictionnaire `CONFIG`. Modifier ces valeurs permet d'ajuster la complexité du problème de pavage.

|  Variable  | Type  | Description |
| :--------: | :---- | :---------- |
| `n_shapes` | `int` | Nombre total de polyominos générés pour la session.        |
| `min_size` | `int` | Surface minimale d'une pièce (en unités de grille).        |
| `max_size` | `int` | Surface maximale d'une pièce (en unités de grille).        |
| `seed`     | `int` | Graine pour figer l'aléatoire et reproduire les résultats. |


## Manipulation des Fonctions

### 1. Point d'entrée principal
La fonction `main()` orchestre la génération, l'assemblage selon les trois heuristiques (H1, H2, H3) et la production des rapports visuels.

```python
def main(n_shapes=10, min_size=3, max_size=8, seed=42, save="compacite"):
    """
    Lance une simulation complète.
    Produit 5 fichiers images analysant l'évolution et la ressemblance.
    """
