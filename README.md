# Logiciel-d-Estimation-de-qualit-de-vin
Logiciel se basant sur une arbre de décision en Programmation orientée objet pour estimer la qualité du vin et gérer les vins 
# Logiciel d'Estimation de Qualité de Vin 🍷

## Description
Ce projet est un **logiciel d'estimation de la qualité du vin** développé en **Programmation Orientée Objet (POO)**. Il utilise un **arbre de décision** pour analyser les propriétés du vin et fournir une estimation qualitative. En plus de l'estimation, le logiciel inclut des fonctionnalités pour la gestion de données sur les vins.

Le projet vise à illustrer l'utilisation de techniques d'intelligence artificielle combinées à des principes de programmation avancés pour résoudre des problèmes pratiques.

## Fonctionnalités
- **Estimation de la qualité du vin** : 
  Analyse les propriétés (acidité, teneur en sucre, pH, etc.) pour estimer la qualité du vin.
- **Gestion des données des vins** :
  - Ajouter, modifier et supprimer des informations sur les vins.
  - Rechercher des vins selon des critères spécifiques (année, région, type, etc.).
- **Utilisation d’un arbre de décision** :
  Implémentation d’un modèle simple pour l’analyse des données du vin.
- **Interface utilisateur** :
  Une interface intuitive pour interagir avec le logiciel.

## Technologies utilisées
- **Langage** : C++ (Programmation Orientée Objet).
- **Structures de données** : Utilisation d’arbres binaires pour implémenter l’arbre de décision.
- **Algorithmique** : Analyse des propriétés pour la prise de décision.

## Architecture du projet
1. **Modules principaux** :
   - **Module Arbre de Décision** : Implémente la structure d’arbre et l’algorithme de décision.
   - **Module Gestion des Vins** : Permet la gestion des informations sur les vins (ajout, suppression, modification).
   - **Module Interface** : Fournit un point d’interaction avec l’utilisateur.

2. **Données d’entrée** :
   - Les propriétés des vins sont saisies ou chargées à partir d’un fichier (par exemple : `data.csv`).
   - Exemples de propriétés : acidité fixe, acidité volatile, pH, teneur en alcool, etc.

3. **Sortie** :
   - Une estimation qualitative du vin (exemple : **"Excellent"**, **"Moyen"**, **"À améliorer"**).
   - Liste des vins gérés.

## Installation

### Prérequis
- **Compilateur C++** : GCC, Clang, ou tout autre compilateur compatible avec C++.
- **IDE recommandé** : Visual Studio Code, CLion, ou autre.
- **Bibliothèque CSV** (optionnel) : Si vous utilisez des fichiers CSV pour stocker les données des vins.

### Étapes d'installation
1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/oliveboss/Logiciel-d-Estimation-de-qualit-de-vin.git
   cd Logiciel-d-Estimation-de-qualit-de-vin
