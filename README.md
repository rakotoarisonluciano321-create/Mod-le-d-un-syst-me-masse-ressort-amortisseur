# Modèle d’un système masse-ressort-amortisseur

## Description
Ce projet consiste à modéliser et simuler un système masse-ressort-amortisseur à l’aide du logiciel Scilab. L’objectif est d’analyser la réponse du système soumis à une force constante (entrée échelon).

## Modèle mathématique
Le système est décrit par l’équation différentielle suivante :

m x''(t) + c x'(t) + k x(t) = F(t)

où :
- m : masse
- c : coefficient d’amortissement
- k : raideur du ressort
- F(t) : force appliquée

## Paramètres utilisés
- m = 1
- c = 0.5
- k = 4
- F(t) = 1

## Méthode
- Mise sous forme d’équations d’état
- Résolution numérique avec la fonction ode de Scilab
- Simulation de 0 à 10 secondes

## Résultats
- Présence d’un dépassement initial
- Oscillations amorties
- Stabilisation vers une position d’équilibre

Le système est donc stable et sous-amorti.

## Fichiers
- simulation.sci : code principal

## Conclusion
Ce projet permet de comprendre le comportement dynamique d’un système masse-ressort-amortisseur et l’influence des paramètres sur sa stabilité.

## Auteur
- Votre nom

## Licence
Projet académique
