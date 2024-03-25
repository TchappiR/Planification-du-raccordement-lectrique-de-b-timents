# Plan-raccordement-reseau-elctrique

# Cas d'usage: Planification du raccordement électrique de bâtiments

## Contexte
Une petite ville a été touchée par des intempéries, entraînant la destruction de plusieurs infrastructures permettant le raccordement des maisons au réseau électrique. Vous avez été embauché par la mairie afin de proposer une planification pour les travaux à effectuer, dans le but de re-raccorder tous les citoyens à la fibre. L'objectif est de rétablir rapidement la connexion pour le plus grand nombre d'habitants avec le budget le plus faible possible
Vous avez été fournis avec deux shapefiles et un fichier CSV. Ces fichiers représentent respectivement les bâtiments, les lignes électriques à déployer pour le raccordement, et l'arbre linéaire du réseau qui décrit les connexions à mettre en œuvre et les coûts de raccordement.
Toutes l’information dont vous avez besoin pour proposer votre planification se situe dans le fichier “reseau_en_arbre.csv”

## Objectifs du Cas d'Utilisation
Votre mission est de créer un plan de raccordement qui priorise les bâtiments les plus simples à raccorder (en minimisant les coûts) tout en maximisant le nombre de prises raccordées. Vous devrez prendre en compte la mutualisation des lignes électriques entre plusieurs bâtiments pour optimiser le plan.

## Données Fournies
1. Shapefile des Bâtiments: Contient les données géospatiales des bâtiments, y compris leurs emplacements.
2. Shapefile des Lignes Électriques: Contient les données géospatiales des lignes électriques à déployer pour le raccordement.
3. Fichier CSV de l'Arbre Linéaire: Fournit une représentation linéaire du réseau, indiquant les connexions et les coûts de raccordement.

## Instructions
1. Analyse Préliminaire:
  * Examinez les shapefiles pour comprendre la disposition géographique des bâtiments et des lignes électriques.
  * Analysez le fichier CSV pour comprendre la structure de l'arbre linéaire du réseau et les coûts associés à chaque connexion.

2. Modélisation du Réseau:
  * Modélisez le réseau électrique en utilisant la théorie des graphes, où les bâtiments sont des nœuds et les lignes électriques sont des arêtes.
  * Intégrez les données de coût dans les arêtes de votre modèle de graphe.

3. Développement de la Métrique de Priorisation:
  * Élaborez une métrique qui évalue chaque bâtiment en fonction de la facilité de raccordement et du coût.
  * La métrique doit favoriser les bâtiments qui peuvent être raccordés avec le moins de dépenses et le maximum de mutualisation des lignes.

4. Planification du Raccordement:
  * Utilisez votre métrique pour établir un ordre de priorité pour le raccordement des bâtiments.
  * Proposez un plan d'action qui détaille l'ordre dans lequel les bâtiments doivent être raccordés.

5. Optimisation:
  * Identifiez les opportunités de mutualisation des lignes pour réduire les coûts.
  * Ajustez votre plan pour maximiser le nombre de prises raccordées.

6. Rapport:
  * Rédigez un rapport expliquant votre méthodologie, votre métrique de priorisation, et le plan de raccordement proposé.
  * Justifiez vos choix et démontrez comment votre plan atteint l'objectif de maximisation des prises raccordées et de minimisation des coûts.

# Livraison Attendue
Un rapport détaillé incluant :

  * Une description de votre métrique de priorisation.
  * Le plan de raccordement des bâtiments avec l'ordre de priorité.
  * Une analyse des coûts et des bénéfices de votre planification.
  * Des cartes issues des shapefiles illustrant le plan de raccordement proposé.
  * Un résumé des défis rencontrés et des solutions apportées.
