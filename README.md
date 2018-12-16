tp2 de machine learning

PLAN

I.	Analyse exploratoire des données (NB5 + EDA)

	1)	Etude des données brutes

		a)	Importation des données
		b)	Analyse des données
		c)	Types des données
		d)	Valeurs manquantes
		e)	Distribution de la variable cible

	2)	Visualisation pandas + seaborn du jeu de données (NB5)

		a)	Corrélation des features ind, reg, car, calc 
		b)	Distribution des features catégorielles
		c)	Nombre de catégories
		d)	Répartition des données binaires

II.	Préparation des données pour l'entraînement des classifieurs  (NB5)

	1)	Suppression de features
	2)	Encodage des données catégorielles (NB4)
	3)	Centrage et réduction des variables continues (NB4)


III.	Entraînement et Tests des modèles

	1)	ACP (voir sous-partie 4))
	
	2)	Régression logistique
		a)	Séparation en train et test
		b)	Cross-validation du niveau de pénalisation
		c)	Courbe ROC
		
	3)	Comparaison d'autres classifieurs via les mesures d'erreur
		a)	Modèles
		b)	Courbe ROC
		c)	Courbe Precision-Recall
		
	4)	Feature Engineering
		a)	Suppression des features avec variance très faible ou nulle (calculée via ACP, faire le lien avec le 1))
		b)	Sélection de Features

