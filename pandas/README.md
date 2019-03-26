# Pandas step by step 


## Introduction 

Pandas est une bibliothèque écrite pour le langage de programmation Python **permettant la manipulation et l'analyse des données**. Elle propose en particulier des structures de données et des opérations de manipulation de tableaux numériques et de séries temporelles. Pandas est un logiciel libre sous licence BSD. 

## Installer pandas sur votre machine 

Comme pour numpy, vous pouvez vérifier que vous n'avez pas pandas avant de l'installer. Pour cela taper la commande 
```
pip3 list
```

Si pandas ne s'affiche pas c'est qu'il n'est pas installé ! 

### Installer pandas

Suivant le type d'installation que vous avez choisi vous pouvez installer pandas de la façon suivante :
- Pour ceux qui ont choisi l'installation manuelle : lancer la commande suivante
```
pip3 install pandas
```
- Pareil pour ceux qui ont choisi l'installation cloud
- Pour ceux qui ont Anaconda numpy est déjà installé nativement. Vous pouvez le vérifier en lançant un notebook jupyter et en tapant la ligne de commande suivante :
```
import pandas as pd 
```
Si la cellule s'execute et passe à la suivante c'est que pandas est bien présent sur votre machine.