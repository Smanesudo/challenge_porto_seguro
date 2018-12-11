tp2 de machine learning

Points à éclaircir 

	- catégorisation des variables : selon le suffixe ou selon le type apparent (il y a des features "cat" qui sont binaires)
	- tri des variables pour la corrélation
	- ce qu'il faut faire exactement dans les parties III et IV
	- quand/où traiter les données test (en même temps que les données train ou après ?)

Plan

I.	Analyse exploratoire des données (NB5 + EDA)

	1)	Etude des données brutes
		a)	Importation des données
		b)	Valeurs manquantes
		c)	Type des données
		
	2)	Visualisation pandas + seaborn du jeu de données (NB5)
		a)	Corrélation des features continues
		b)	Corrélation des features discrètes
		c)	Distribution des features
		d)	Distribution de la variable cible
		
II.	Préparation des données pour l'entraînement des classifieurs  (NB5)

	1)	Suppression de features (valeurs manquantes)
	2)	Encodage des données catégorielles (NB4)
	3)	Centrage et réduction des variables continues (NB4)
	4)	Matrice des features
	5)	Enregistrement des données traitées (pickle)

III.	Entraînement et Tests

	1)	Choix d'algo (Régression logistique par ex) et entraînement
	2)	Cross-validation du niveau de pénalisation
	3)	Comparaison d'autres classifieurs via les mesures d'erreur
		•	Courbe ROC
		•	Courbe Precision-Recall
		
IV.	Sélection de features (par permutation)

	1)	Création d'un classifieur Light GBM Random Forest
	2)	Comparaisons
