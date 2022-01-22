# machineTextuelle
Bonjour à toustes,
ici se trouve le répertoire des fichiers de la "machine textuelle" qui fait partie du projet "le nouveau Decameron"
Le fichiers principaux:
- le fichier TouchDesigner jouable sur macos et Windows machineTextuelle.toe
- le tableau répertoriant les répliques, les didascalies et tout le reste...
- un dossier images contenant des fichiers image :=)
- un dossier sons contenant des fichiers son ;-)

Quelques règles à respecter:
- ne pas toucher au fichier .toe si on ne sait pas :-(
- 
dans le tableau :
- ne pas changer les en-têtes de collone
- chaque réplique doit commencer par un N° qui suit celui de la réplique précédente
- chaque réplique doit être suivie d'une ligne vide puis d'un numéro
- chaque répilque doit comprendre au moins un mot-clef
- on peut diviser une ligne avec '/'

dans les colonnes b1Jx "GO" active le bouton pour passer à la réplique suivante
dans les colonnes b2Jx "NEXT" active le vibreur du téléphone correspondant

dans la colonne "son", si le nom qui est écrit correspond exactement à un fichier .wav placé dans le dossier son, il est joué.
il continue à jouer tant qu'il est écrit dans la colonne. (le nom écrit sans le suffixe)

dans la colonne "image", même chose avec un fichier .jpg du dossier images (sans suffixe)

attention aux encodages quand vous faites un "copier-coller", je recommande d'éditer le texte dans Modern CSV
