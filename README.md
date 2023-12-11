## Description:

Ce plugin développé pour le jeu de role Etherion, permet de simuler des lancés de dé dans minecraft 1.16.



## Commande:

/roll XdY [[+;-]Z] [global]

- X >= 1 > nombre de dé à lancer
- Y >= 1 > nombre de face du dé     		        
- Z = valeur libre > (Optionnel) bonus/malus à ajouter au jet
- global > (Optionnel) rendre le message global

![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/afb32531-0e15-4c96-8eef-7d9f2a21cefd)

De base, le message du jet est envoyé à tous les joueurs dans les 30 blocks autour du joueur qui fait un jet.
L'option _global_ permet d'envoyer le message du roll à tous les joueurs connectés du serveur.

Les critiques (succes et echec) sont uniquement disponible lors de jet de dé 20.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/2a70fb64-2741-4d76-b0a0-051472657020)
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/66d81c15-b77f-40cb-86ad-5e27f7121ec3)

Lorsque le joueur lance plusieurs dés simulanément avec un bonus/malus, celui-ci sera appliqué uniquement sur le premier jet sauf en cas d'echec ou succes critique.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/b2472610-7af2-4484-8f1b-9161abcaafdf)
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/92f8d5b1-7257-4c65-8484-6922545c39bb)


## Exemples d'utilisation:

- /roll 1d20‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ > Lance 1 dé 20.\
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/35d6efef-edc2-4c3b-90e8-c54dadaa169f)

- /roll 1d20 5            > Lance 1 dé 20 avec un bonus de 5.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/28473eea-7688-4e67-b3f1-0579f794c175)

- /roll 1d12 -3 globalㅤㅤㅤㅤㅤㅤ    > Lance 1 dé 12 avec un malus de 3 et le message sera donc envoyé à tous les joueurs.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/86bd52d4-be19-47c4-9338-30fa8ccd109c)
 
- /roll 3d6 +1            > Lance 3 dé 6 avec un bonus de 1 au premier jet.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/aa9cb105-d2b8-47ef-a3af-83ee3dd0c371)






