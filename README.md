# Idées de projet Arduino

SOMMAIRE:
* [Kamisado connecté](#Kamisado_connecte)

## Kamisado connecté

Le kamisado est un jeu de plateau stratégique 1v1 dont voici [les regèles](http://www.yucata.de/en/Rules/Kamisado).
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
