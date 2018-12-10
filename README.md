# challenge_porto_seguro
tp2 de machine learning  

Plan :

I.	Analyse exploratoire des données (NB5 + EDA)
  1)	Etude des données brutes
    •	Importation des données
    •	Valeurs manquantes
    •	Type des données
  2)	Visualisation pandas + seaborn du jeu de données (NB5)
    •	Corrélation des features continues
    •	Corrélation des features discrètes
    •	Distribution des features
    •	Distribution de la variable cible
    
II.	Préparation des données pour l'entraînement des classifieurs  (NB5)
  •	Suppression de features (celle ayant trop de valeurs manquantes et les features calc)
  •	Encodage des données binaires et catégorielles (NB4)
  •	Centrage et réduction des variables continues (NB4)
  •	Matrice des features
  •	Enregistrement des données traitées (pickle)
  
III.	Entraînement et Tests
  1)	Choix d'algo (Régression logistique par ex)
  2)	Cross-validation du niveau de pénalisation
  3)	Comparaison d'autres classifieurs via les mesures d'erreur
    •	Courbe ROC
    •	Courbe Precision-Recall
    
IV.	Sélection de features (par permutation)
  1)	Création d'un classifieur Light GBM Random Forest
  2)	Comparaisons
