### Description

Ce plugin développé pour le jeu de role Etherion, permet de simuler des lancés de dé dans minecraft 1.16.



### Commande:

/roll XdY [[+;-]Z] [global]

- nb de dé a lancer:         	X >= 1
- nb face du dé:     		      Y >= 1
- bonus/maus à ajouter au jet	Z = libre

De base le message du roll est envoyé à tous les joueurs dans les 30 block autour du joueur.
L'option _global_ permet d'envoyer le message du roll à tous les joueurs connectés du serveur.

Les echecs critique sont toujour à 1 et les succes critique sont toujours à 20.
Lorsque le joueur lance plusieurs dés simulanément avec un bonus/malus, celui-ci sera appliqué uniquement sur le premier jet sauf en cas d'echec ou succes critique. 


Exemples d'utilisation:

- /roll 1d20‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ > Lance 1 dé 20.
- /roll 1d20 5            > Lance 1 dé 20 avec un bonus de 5.
- /roll 1d12 -3 globalㅤㅤㅤㅤㅤㅤ    > Lance 1 dé 12 avec un malus de 3 et le message sera donc envoyé à tous les joueurs.
- /roll 3d6 +1            > Lance 3 dé 6 avec un bonus de 1 au premier jet.
