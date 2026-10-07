# PE_Compétition_informatique

> **In English:** team project at École Centrale de Lyon (2025-2026) on competitive programming. It contains a documented algorithms handbook (data structures, graphs, dynamic programming, number theory, geometry, metaheuristics) and a set of about 45 solved CSES/Codeforces problems, written as Python Jupyter notebooks. The content is in French.

Projet d'Étude n°70 (PE70) réalisé en équipe en 1re année à l'École Centrale de Lyon (2025-2026). Il porte sur la programmation compétitive et l'algorithmique avancée.

## Contexte et objectifs

À Centrale Lyon, l'entraînement à la programmation compétitive reposait jusqu'ici sur des initiatives étudiantes ponctuelles, d'où des résultats irréguliers au SWERC : 39e/107 en 2023, puis 98e/141 en 2024. Le projet visait à mettre en place un dispositif d'entraînement durable et réutilisable par les promotions suivantes, autour de quatre axes :

1. **Un socle théorique :** un livret d'algorithmes documenté, avec les preuves de complexité.
2. **Un dispositif d'entraînement :** un livret d'exercices classés par thème et par difficulté.
3. **Un programme d'entraînement :** une pratique régulière sur Codeforces et la participation à des concours (Prologin, Midnight Code Cup, SWERC).
4. **Un événement compétitif :** l'organisation d'une compétition d'algorithmique à Centrale Lyon.

## Contenu du dépôt

| Fichier | Description |
|---|---|
| [`livret_algorithmes.ipynb`](livret_algorithmes.ipynb) | Socle théorique : cours, analyses de complexité et implémentations Python exécutables |
| [`livret_exercices.ipynb`](livret_exercices.ipynb) | Environ 45 problèmes CSES / Codeforces, avec deux indications et une correction détaillée chacun |

Les livrets sont rédigés en Jupyter Notebook. Ce format permet d'alterner explications mathématiques (Markdown) et code exécutable, et donc de vérifier que chaque algorithme fonctionne, y compris sur les cas limites.

### Livret d'algorithmes
Chaque algorithme est présenté avec sa modélisation (états, transitions, cas de base), son analyse de complexité et une implémentation de référence.

1. **Structures de données :** piles, files, BST, segment trees (avec lazy propagation), Fenwick trees, tas, Union-Find, tries
2. **Graphes :** BFS/DFS, Dijkstra, Bellman-Ford, Floyd-Warshall, Kruskal, Prim, flot maximum, composantes fortement connexes, cycles
3. **Programmation dynamique :** top-down et bottom-up, sac à dos, LIS en O(n log n), LCS, DP sur intervalles, sur arbres, bitmask DP, optimisation Divide & Conquer
4. **Chaînes de caractères :** hachage polynomial, KMP, Z-algorithm
5. **Mathématiques :** arithmétique modulaire, théorème des restes chinois, Euclide étendu, crible d'Ératosthène, combinatoire
6. **Géométrie :** produits scalaire et vectoriel, enveloppe convexe, intersection de segments, aire et point dans un polygone
7. **Techniques algorithmiques :** recherche binaire et ternaire, two pointers, algorithmes gloutons, backtracking
8. **Heuristiques :** recherche locale, recuit simulé, beam search pour les problèmes NP-difficiles

### Livret d'exercices
Les problèmes sont regroupés en 9 thèmes : graphes, programmation dynamique, structures de données, théorie des nombres, texte, géométrie, flots et graphes bipartis, arbres, heuristiques. Pour chaque exercice, on suit une démarche « modéliser d'abord, coder ensuite » :
- l'énoncé et les contraintes ;
- deux indications progressives ;
- une correction détaillée avec l'analyse de complexité et une implémentation.

## Résultats

- **Prologin :** deux membres qualifiés pour la finale nationale (3e et 4e de leur épreuve régionale). Centrale Lyon est classée 37e parmi les écoles inscrites.
- **Midnight Code Cup :** participation avec deux équipes de trois sur des problèmes d'optimisation NP-difficiles.
- **SWERC :** l'équipe a été bénévole lors de l'édition organisée à Lyon.
- **Compétition interne :** organisation le 4 juin 2026 d'une compétition au format SWERC, hébergée sur Codeforces.
- **Volume de travail :** environ 750 heures au total, soit plus de 120 heures par membre.

## Utilisation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/timeoio/PE_Competition_informatique.git
   ```
2. Ouvrez les notebooks avec Jupyter ou VS Code (extension Jupyter, Python 3).
3. Étudiez une notion dans le livret d'algorithmes, puis entraînez-vous sur les problèmes du même thème dans le livret d'exercices avant de lire la correction.
4. Complétez avec une pratique régulière sur [Codeforces](https://codeforces.com) et le [CSES Problem Set](https://cses.fi/problemset/).

## Équipe

**Élèves :** Martin Mahérault, Pierre Sagnard, Yann Sepulchre, Timéo Larrede, Xingchuan Jia, Sena Nakai

**Tuteurs :** Charles-Edmond Bichot, Romain Vuillemot, Antoine Becquet. **Conseillère :** Amaya Fabregoule

Dépôt original de l'équipe : [Xenow91/PE_Competition_informatique](https://github.com/Xenow91/PE_Competition_informatique)
