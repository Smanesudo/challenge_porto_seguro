Problèmes à résoudre/points à développer ou éclaircir :

	1)	Faut-il ajouter la corrélation selon les groupes de features ('calc', 'ind,..) ?
	2)	Faut-il vraiment supprimer les features binaires à majorité de zéros alors qu'à la base on est sur un problème de jeu de données déséquilibré ?
	3)	Comment exploiter et expliquer les corrélations ?
	4)	Pourquoi enlève-t-on 'id' dans le train et pas dans le test ?
	5)	Que faire des binaires cachés dans les catégorielles ?
	6)	Faut-il prendre le temps d'interpréter (deviner) les variables catégorielles ? (j'ai quelques idées et apparemment d'autres aussi)
	7)	Pourquoi faut-il utiliser RandomForest une fois pour obtenir les importances des features (et comment ce mécanisme fonctionne t-il ?) puis une autre fois en entraînement de modèle ?
	8)	Faut-il faire des pipelines pour nos tests ?

Idées d'implementation :

	1)	Polynômes de features
	2)	Optimisation de la mémoire (jusqu'à 10 Go de RAM utilisés !). Voir s'il y a sparsity
	3)	Améliorer les graphes avec gridspec
