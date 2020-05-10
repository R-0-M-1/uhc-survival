<h1>Annexe</h1>

<h3>Objectifs</h3>

Les objectifs sont divisés en différentes catégories rapportant un certain score en fonction de la catégorie et d'un multiplicateur de score fonction de la difficulté et de la réussite.

<h5>Score par catégorie</h5>

| Catégories | Construction | Redstone | Exploration | Aventure | Equipe |
| ---------- | ------------ | -------- | ----------- | -------- | ------ |
| Score      | 2            | 2        | 7           | 100      | 120    |

<h5>Multiplicateur de Score</h5>

| Difficulté\Réussite | Nul       | Bof  | Ok   | Cool | Génial |
| ------------------- | --------- | ---- | ---- | ---- | ------ |
| Très simple         | à refaire | 0.25 | 0.5  | 0.75 | 1      |
| Simple              | à refaire | 0.5  | 0.75 | 1    | 1.5    |
| Modéré              | à refaire | 0.75 | 0    | 1.5  | 2      |
| T                   | à refaire | 1    | 1.5  | 1    | 2.5    |
| Très difficile      | à refaire | 1.5  | 2    | 2.5  | 3      |

<h5>Construction</h5>

* Construire la mairie
* Construire la ferme
* Construire la forge
* Construire la maison du bûcheron
* Construire village à villageois fortifié
* Construire la cité aquatique
* Construire le port
* Construire la gare
* Construire la château
* Construire le marché
* Aménager le spawn
* Construire le bâteau de pirate
* Construire le dirigeable
* Construire l'aquarium avec les poissons
* Construire la base du nether
* Construire la muraille de la ville
* Construire la mine avec accès facile depuis la surface
* Faire un pixelart
* Construire le temple du culte du serveur
* Construire la statue du Dieu du serveur
* Construire le champ de tournesol
* Construire les rues de la ville avec leur nom

<h5>Redstone</h5>

* Construire la ferme à poulet automatisé
* Construire la ferme à melon et pastèque
* Aménager un spawner en usine à xp.
* Construire la tour à mob
* Construire l'usine à fer
* Construire l'usine à blaze
* Construire le système de minecart à travers la ville
* Construire usine à laine
* 

<h5>Exploration</h5>

* Trouver biome Jungle
* Trouver biome Messa
* Trouver biome Ice Spike
* Trouver temple des mers
* Trouver temple du sable
* Trouver temple de la jungle
* Trouver le stonghold
* Trouver forteresse du nether
* Trouver forteresse de l'end avec bâteau à elytra
* Récolter tous les types de poissons différents (vivant)

<h5>Aventure</h5>

* Récolter les têtes de creeper, zombie et squelette

* Récolter le trident
* Tuer le gardien du temple

* Tuer l'ender dragon
* Tuer le wither

<h5>Equipe</h5>

* Construire la maison de chaque membre
* Construire le quartier générale de l'équipe



<h3>Bonus</h3>

* Le marteau de Thor (Trident Recul X + Solidité X+ Effet éclair)
* Le Ghast-Bow (Arc qui lance des boules de feu)
* La Pelteuse  (Pelle en diamant Efficacité X + Solidité X )
* L'Annihilator (Pioche en diamant Efficacité X + Solidité X)
* Excalibur (Epée en diamant Tranchant X + Solidité X)



<h3>Préparation du Scoreboard</h3>

```
/scoreboard objectives add Score dummy "Score"
/scoreboard objectives setdisplay sidebar Score
/scoreboard players set EquipeBleu Score 0
/scoreboard players set EquipeRouge Score 0
/scoreboard players set EquipeVerte Score 0
/scoreboard players set EquipeJaune Score 0
/team add EquipeBleu
/team add EquipeRouge
/team add EquipeVerte
/team add EquipeJaune
/team modify EquipeBleu color aqua
/team modify EquipeRouge color red
/team modify EquipeVerte color green
/team modify EquipeJaune color yellow
/team join EquipeBleu EquipeBleu
/team join EquipeRouge EquipeRouge
/team join EquipeVerte EquipeVerte
/team join EquipeJaune EquipeJaune
/team modify 
```

* Pour ajouter une personne dans une équipe

```
/team join {Equipe} {Joueur}
```

