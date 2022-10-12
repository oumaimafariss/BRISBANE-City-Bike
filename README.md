# Projet final: BRISBANE City Bike
Dans le cadre de notre enseignement sur les Big Data, nous avons réalisé ce projet pour mettre en pratique nos compétences en matière de Spark. 
Nous avons utilisé la base de données des stations vélos dans la ville BRISBANE. 
L'objectif de ce travail est d'effectuer un clustering par la méthode de KMeans ainsi que la visualisation du résultats sur une carte. 
La structure du projet est comme suit:  

-Un google colab contenant les réponses sur le sujet
 
-Dossier data contient le jeux de données utilisé  

-Ficheir properties.conf dont les configuration nécessaires pour ce projet à savoir:
	* le chemin des données
 	* le chemin de sauvgarde 
	* le nombre de classe pour la méthode KMeans  
  

-Dossier exported contenant le fichier final part-00000-5da9728c-d154-406b-b220-6a5b7c5c27a5-c000.csv les colonnes suivantes:
       * latitude
       * longitude  
       * prediction  
  
-Dossier output contenant Bristol-City-bike.html qui est la carte sauvgardée sous format HTML


