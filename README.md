# Simulation des Variables Aléatoires et des Chaînes de Markov

## Description du Projet

Ce projet vise à simuler des variables aléatoires à valeurs dans un ensemble fini et à explorer les chaînes de Markov. Il inclut la création de plusieurs fonctions Python pour analyser et simuler les comportements des chaînes de Markov et des distributions associées.

## Table des Matières

- [Généralités sur les Chaînes de Markov](#généralités-sur-les-chaînes-de-markov)
- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Exemples](#exemples)
- [Contributions](#contributions)
- [Licence](#licence)

## Généralités sur les Chaînes de Markov

Une chaîne de Markov est un processus stochastique où l'état futur dépend uniquement de l'état présent et non de l'état passé. Dans ce projet, nous travaillons avec une matrice de transition \( P \), où \( P_{i,j} \) représente la probabilité de passer de l'état \( i \) à l'état \( j \).

## Fonctionnalités

Le projet comprend plusieurs fonctions clés :

1. **accessibleN(i, j, P, N)** : Détermine si un chemin de longueur \( N \) existe entre les états \( i \) et \( j \).
2. **accessible(i, j, P)** : Vérifie si un chemin existe entre \( i \) et \( j \).
3. **recurrente(i, P)** : Vérifie si l'état \( i \) est récurrent.
4. **classes(P)** : Retourne les classes de la chaîne.
5. **recurrente(P)** : Retourne les états récurrents.
6. **simulationX(S)** : Simule une variable aléatoire donnée une liste \( S \).
7. **Trajectoire(l)** : Retourne une trajectoire de la chaîne de Markov de \( 0 \) à \( l \).
8. **T(i)** : Calcule le temps de premier retour à l'état \( i \).

## Installation

Pour exécuter ce projet, vous aurez besoin de Python et de certaines bibliothèques. Assurez-vous d'avoir installé Python 3.x et les bibliothèques suivantes :

```bash
pip install numpy matplotlib
