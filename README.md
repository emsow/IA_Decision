# IA-Decision

Ce dépôt contient les solutions pour trois travaux pratiques réalisés dans le cadre du cours "IA et Décision". Chaque projet explore des techniques d'intelligence artificielle et d'optimisation pour résoudre des problèmes concrets.


## 1. TP1 : Optimisation du plan d'acquisition d'un satellite d'observation terrestre

Ce projet modélise l'optimisation du plan d'acquisition d'un satellite optique. L'objectif est de **maximiser le nombre d'images de haute qualité** tout en respectant un ensemble de contraintes techniques complexes.


Le problème est formulé comme un problème de **programmation linéaire en nombres entiers mixtes (PLNIM)**. Le modèle intègre des contraintes sur la mémoire du satellite, le temps de transition entre les images, l'affectation des instruments, la probabilité de défaillance des instruments et les conditions météorologiques.

La solution est implémentée en utilisant un langage de modélisation mathématique **Zimpl**. Les fichiers de code résolvent le modèle pour déterminer le plan d'acquisition optimal.



## 2. TP2 : Le robot nettoyeur (Processus de Décision Markovien)

Ce projet aborde le problème du **robot nettoyeur** en utilisant un **Processus de Décision Markovien (MDP)**. L'objectif est de trouver une politique optimale qui maximise la récompense à long terme du robot.


Le robot évolue dans des états définis (salon propre ou sale, chargeur propre ou sale) et choisit entre les actions "nettoyer" ou "charger". Les transitions d'état sont probabilistes, ce qui rend le problème idéal pour une approche par MDP.


Le code développé dans un notebook en **Python**  utilise la bibliothèque **`pymdptoolbox`** pour calculer la politique optimale en fonction de divers paramètres (récompenses, probabilités de panne, etc.)


## 3. TP3 : Partage équitable des coûts de covoiturage

Ce projet applique les principes de la **théorie des jeux coopératifs** pour résoudre un problème de partage équitable des coûts pour un trajet de covoiturage. L'objectif est de trouver une répartition des coûts qui soit à la fois équitable et stable pour tous les participants.


Le problème implique le partage des coûts d'un trajet entre plusieurs voyageurs. Il s'agit de tester différentes méthodes d'allocation (proportionnelle, par séparation) et de vérifier leur stabilité à l'aide de concepts tels que le **Stand-Alone Test** et le **Noyau**.


La solution est présentée dans un notebook **Jupyter** en **Python**. Le code calcule les allocations de coûts et vérifie si elles satisfont les critères de stabilité de la théorie des jeux coopératifs.
