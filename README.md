## Description:

Ce plugin développé pour le jeu de role Etherion, permet de simuler des lancés de dé dans minecraft 1.16.



## Commande:

/roll XdY [[+;-]Z] [global]

- X >= 1           > nombre de dé à lancer
- Y >= 1           > nombre de face du dé     		        
- Z = valeur libre > (Optionnel) bonus/malus à ajouter au jet
- global           > (Optionnel) rendre le message global

![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/53361037-ae61-45a4-a979-a6fe6d85058f)

De base, le message du jet est envoyé à tous les joueurs dans les 30 blocks autour du joueur qui fait un jet.
L'option _global_ permet d'envoyer le message du roll à tous les joueurs connectés du serveur.

Les critiques (succes et echec) sont uniquement disponible lors de jet de dé 20.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/3e0dd157-500a-4880-8854-b50d719d9d91)
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/3e63e0f1-504e-4d3b-99f3-9bee8ca5059a)

Lorsque le joueur lance plusieurs dés simulanément avec un bonus/malus, celui-ci sera appliqué uniquement sur le premier jet sauf en cas d'echec ou succes critique.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/e85fe689-5932-4b12-9373-992c4fff77f5)
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/9822dad7-65be-4403-8426-7a7ba5aac222)
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/dbdc4698-8bac-4162-b59a-edb147327455)



## Exemples d'utilisation:

- /roll 1d20              > Lance 1 dé 20.\
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/6804b235-e709-4375-8b57-5e62c319c925)

- /roll 1d20 5            > Lance 1 dé 20 avec un bonus de 5.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/8b3b4893-48be-4ab9-97d9-5412db708ab1)

- /roll 3d6 +1            > Lance 3 dé 6 avec un bonus de 1 au premier jet.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/764ad5c2-242e-4538-a865-b3ee21c3ce1c)

- /roll 1d12 -3 global    > Lance 1 dé 12 avec un malus de 3 et le message sera donc envoyé à tous les joueurs.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/438d40df-5e9f-4a22-b8ae-3fad3dbb6875)

- /roll 2d12 global       > Lance 2 dé 12 et le message sera donc envoyé à tous les joueurs.
![image](https://github.com/DamienEvrard/DiceRollerPluginMinecraft/assets/55134961/795fbb7c-7bcc-4178-ab30-5f3118809c93)






##Credit:
[Say2Slay](https://github.com/Say2Slay)
