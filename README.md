# TRSante

1er fichier : Premiere_approche

Dans une première partie, analyse primitive des données, extraction de statistiques globales sur les G4 : positions, tailles, types, répartition, clusters.

Dans une seconde partie, création d'un jeu de données de positions aléatoires, dont les autres caractéristiques sont les mêmes : mêmes répartitions de taille, même nombre de G4 par chromosome, même nombre de G4 par type de G4. La répartition des positions est uniforme sur le chromosome, et les chevauchements sont ensuite supprimés.

Dans une troisième partie, comparaison des analyses primitives de la base de données avec les mêmes statistiques relevées sur les positions aléatoires. Comparaison du pourcentage de G4 en cluster : 3 fois moins de G4 en cluster sur les positions aléatoires => mise en évidence d'un phénomène de pression sélective sur les clusters qui ne sont pas le fruit d'un positionnement aléatoire.

___________________________________________________________________

2ème fichier : Creation_des_fichiers_complets_de_mutation

Fichier servant à générer des datasets complets en regroupant ou recoupant des informations de différents datasets.

Dans une première partie, ajout d'une colonne "séquence" dans les datasets afin d'avoir les séquences explicites des G4 / des positions aléatoires générées.

Dans une seconde partie, création pas à pas des datasets recensant les mutations ayant eu lieu dans des G4 avec passage non visible par du script bash.

Dans une troisième partie, création pas à pas des datasets recensant les mutations ayant eu lieu sur les portions aléatoires du génome générées avec passage non visible par du script bash.

____________________________________________________________________

3ème fichier : Mutations

Analyse des mutations des G4

____________________________________________________________________

4ème fichier : Mutations_random

Analyse des mutations des positions random, et comparaisons des données à celles résultant de l'analyse des mutations des G4 (cf Mutations)

