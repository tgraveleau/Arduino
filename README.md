# Idées de projet Arduino

SOMMAIRE:
* [Kamisado connecté](#kamisado-connect%C3%A9)
* [Plateau Yu-Gi-Oh](#plateau-yu-gi-oh)

## Kamisado connecté

Le kamisado est un jeu de plateau stratégique 1v1 dont voici [les règles](http://www.yucata.de/en/Rules/Kamisado).
L'idée est de faire le plateau de jeu avec autant de capteurs que de cases. Chaque capteur va détecter si une tour est présente sur la case. Le plateau sera rendu en 3D sur un smartphone et permettra de visionner le plateau et les mouvements de tours via des animations.

### Plateau de jeu
* Composé d'autant de capteurs que de cases
* Composé de leds de couleurs pour faire les cases du plateau
* Lorsqu'on lève une tour du plateau, toutes les leds s'éteignent sauf celles des cases dont on peut se rendre
* Lorsqu'on pose une tour sur une mauvaise case, les leds s'allument en rouge et le mouvement est refusé
* Lorsqu'un joueur gagne, les leds s'illuminent de façon aléatoire

### Application
* Pourrait faire des animations
* Permet de lancer la partie en donnant des noms de joueurs
* Affiche les messages type "mauvais déplacement" ou "X a gagné"
* Affiche les points

### Moteur
* Enregistre les joueurs
* Compte les points
* Renvoie les positions où les tours peuvent se rendre
* Envoie les messages

## Plateau Yu-Gi-Oh

On met des capteurs, on pose les cartes dessus, sur une application, on voit le monstre qui apparait.

* Détection de la carte
* Grosse partie de visuel avec des animations sur les monstres (invocation, attaque, etc)
* Led qui clignote quand un joueur perd des LP
* Ce genre de conneries
