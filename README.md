tp2 de machine learning

Plan :

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

	1)	Suppression de features (valeurs manquantes, binaires à très grande majorité de zéros et calc)
	2)	Encodage des données binaires et catégorielles (NB4)
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
