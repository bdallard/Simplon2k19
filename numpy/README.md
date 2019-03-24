# Numpy step by step 

## Introduction 
NumPy est une extension du langage de programmation Python, **destinée à manipuler des matrices ou tableaux multidimensionnels ainsi que des fonctions mathématiques opérant sur ces tableaux.**
Plus précisément, cette bibliothèque logicielle libre et open source fournit de multiples fonctions permettant notamment de créer directement un tableau depuis un fichier ou au contraire de sauvegarder un tableau dans un fichier, et manipuler des vecteurs, matrices et polynômes.
NumPy est la base de SciPy, regroupement de bibliothèques Python autour du calcul scientifique.

Vous pouvez bien sur consulter la [documentation officielle](https://docs.scipy.org/doc/numpy-1.13.0/reference/). 

## Installer numpy sur votre machine 

### Vérifier que vous n'avez pas numpy : 
Avant d'installer numpy, vérifions qu'il n'est pas présent sur votre machine avec la commande suivante :
```
pip3 list 
```
Si numpy ne s'affiche pas c'est qu'il n'est pas installé. 

### Installation 
Suivant le type d'installation que vous avez choisi vous pouvez installer numpy de la façon suivante : 
- Pour ceux qui ont choisi l'installation manuelle : lancer la commande suivante  
```
pip3 install numpy
```
- Pareil pour ceux qui ont choisi l'installation cloud 
- Pour ceux qui ont Anaconda numpy est déjà installé nativement. Vous pouvez le vérifier en lançant un notebook jupyter et en tapant la ligne de commande suivante : 
```
import numpy as np
```

Si la cellule s'execute et passe à la suivante c'est que numpy est bien présent sur votre machine. Dans le cas contraire vous allez avoir une erreur du type `Not Found`. 


