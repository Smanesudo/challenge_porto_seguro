tp2 de machine learning


PLAN A REVOIR

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

	1)	Régression logistique
		a)	Séparation en train et test
		b)	Cross-validation du niveau de pénalisation
		c)	Courbe ROC
	
	2)	Comparaison d'autres classifieurs via les mesures d'erreur
		a)	Modèles
		b)	Courbe ROC
		c)	Courbe Precision-Recall
	
	3)	Feature Engineering
		a)	Suppression des features avec variance très faible ou nulle
		b)	Sélection de Features
