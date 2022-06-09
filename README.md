# ACS-TSP
Implémenter l'algorithme Ant Colony Systems (ACS) appliqué pour résoudre le problème du voyageur de commerce (TSP)
##  Comment fonctionne le code
  L’algorithme Ant Colony System peut être utilisé pour trouver le chemin le plus court dans un 
  graphe en employant le même mécanisme décentralisé exploité par les colonies de fourmis à 
  la recherche de nourriture. Dans ce modèle, chaque agent (c’est-à-dire la fourmi) construit une 
  tournée dans le graphe en choisissant à chaque nœud le prochain nœud à visiter en fonction 
  d’une probabilité associée à chaque nœud. La probabilité qu’une fourmi choisisse un nœud 
  spécifique à tout moment est déterminée par la quantité de phéromone et le coût (c’est-à-dire 
  la distance entre le nœud actuel i et le nœud suivant j, où le nœud j n’a pas encore été visité) 
  associés à chaque arête.

##  Comment utiliser le code
  Choisissez le nombre de nœuds et de fourmis que vous souhaitez avoir dans la simulation. 
  Cliquez sur le bouton SETUP pour créer un graphique aléatoire, une nouvelle colonie de 
  fourmis, et dessiner un tour initial sur le graphique. Cliquez sur le bouton GO pour démarrer 
  la simulation. 
  Normalement au cours temps on obtient le temps minimal pour résoudre ce problème TSP 
  qu’on a généré avec le plus court chemin cité, la fourmi nous ayant permis de l’avoir et au 
  bout de quelle itération obtient-on ce résultat (information disponible dans la Command 
  center)
  Le bouton RESET conserve le même graphe que celui généré par l’opération SETUP, mais il 
  réinitialise tout le reste de l’algorithme (c’est-à-dire qu’il détruit toutes les fourmis et les 
  arêtes du graphe et efface tous les tracés). Le bouton RESET permet à l’utilisateur d’exécuter 
  plusieurs tests avec le même graphique pour la collecte de données. 
