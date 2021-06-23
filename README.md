# ElementList
Récupérer des éléments dans une liste 
Pour récupérer le premier élément, nous l'avons-vu précédemment, on utilise les crochets et l'indice 0.

Pour récupérer le dernier élément, peu importe la taille de la liste, on utilise l'indice -1 !

Pour récupérer les deux premiers éléments de la liste, on utilise une syntaxe un peu spéciale, qui se nomme 'slicing'.

En effet, plutôt que de spécifier un seul indice entre les crochets, on peut spécifier un indice de départ et un indice de fin.

Ainsi, pour récupérer les deux premiers éléments, on peut utiliser la syntaxe suivante :

ma_liste[0:2] 

Et puisque nous commençons depuis le début de la liste, on n'a même pas besoin d'indiquer le 0 et Python comprendra qu'on veut commencer depuis le début de la liste, jusqu'au deuxième élément inclus :

ma_liste[:2] 

Pour récupérer les deux derniers éléments, peu importe la taille de la liste, on utilise là encore un indice négatif et toujours le même principe de 'slicing' :

ma_liste[-2:] 

Encore une fois, pas besoin d'indiquer un indice après les deux points, on peut tout simplement laisser le deuxième indice vide, et le slice ira jusqu'à la fin de la liste.
