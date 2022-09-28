# Idées de projet Arduino

SOMMAIRE:
* [Kamisado connecté](#kamisado-connect%C3%A9)

## Kamisado connecté

Le kamisado est un jeu de plateau stratégique 1v1 dont voici [les règles](http://www.yucata.de/en/Rules/Kamisado).
L'idée est de faire un plateau de jeu rempli de led et contenant autant de capteurs que de cases. Chaque capteur va détecter si une tour est présente sur la case. Une application permettra aux joueurs d'interragir avec le jeu ou bien de visualisé les messages envoyés par le moteur, le score etc ...

### Plateau de jeu
* Composé d'autant de capteurs que de cases
* Composé de leds de couleurs pour faire les cases du plateau
* Lorsqu'on lève une tour du plateau, toutes les leds s'éteignent sauf celles des cases sur lesquelles on peut se rendre
* Lorsqu'on pose une tour sur une mauvaise case, les leds s'allument en rouge, le mouvement est refusé et le jeu arrêté
* Lorsqu'un joueur gagne, les leds s'illuminent de façon aléatoire

### Application
* Permet de lancer la partie en initialisant les noms de joueurs
* Affiche les messages type "mauvais déplacement" ou "X a gagné"
* Affiche les points

### Moteur
* Enregistre les joueurs
* Compte les points
* Renvoie les positions où les tours peuvent se rendre
* Envoie les messages
