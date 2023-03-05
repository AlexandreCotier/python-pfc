
# Cahier des charges

Le projet doit : 
- utiliser PyGame
- la communication réseau
- utiliser en partie la programmation orientée objet
- être un jeu jouable à plusieurs

# Travail réalisé

Le travail réalisé consiste à créer un pierre feuille ciseaux jouable sur le réseau à plusieurs.
Il est séparé en 2 parties : le côté serveur et le côté client.
Le client récupère les informations envoyé par le serveur sous forme d'objets grâce à la librairie Pickles et crée ainsi son affichage autour de ça.

Le jeu est théoriquement jouable à travers internet bien qu'il faille ouvrir les ports de sa box internet et définir l'adresse IP dans la classe network.py et server.py.

# Comment le lancer ?

Si vous utilisez PyCharm, il faudra crée deux configurations : l'une pour le fichier server.py et l'autre pour le client.py. Veuillez à bien cocher "Allow multiple instances" pour la configuration du client afin de pouvoir lancer deux instances et l'essayer sur une même machine.
