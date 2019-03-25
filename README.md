# Simplon 2k19

## Introduction  
Ce repository contient les différentes séances abordées durant la formation Data IA Simplon 2019. Il servira de fil conducteur durant les cours.

## Installer vos outils de travail 
Afin de commencer ce cours sereinement vous devez disposer d'un certain nombre d'outils, notamment : 
- Avoir python sur sa machine (afin de vérifier si python est sur votre machine lancer un teminal / invité cmd et taper `python --version` ) 
- Avoir Jupyter ainsi que les différentes librairies python (pandas, numpy, matplotlib...) 

### Plusieurs choix d'installation : 
Pour avoir les différents outils ci-dessus vous disposez donc de plusieurs choix :  
- Vous pouvez opter pour **une installation dite manuelle** dans ce cas la voir ci-dessous. 
- Si vous n'avez pas envie de taper toute ces commandes, vous pouvez optez pour **l'obtention de l'environnement de développement (IDE)** [Anaconda](https://www.anaconda.com/distribution/). Le logiciel Anaconda est disponible aussi bien sur Mac OS que sur Windows et contient python3 (la version 3 de python est recommandé) ainsi que les autres outils énoncés ci-dessous. 
- Si vous vous sentez l'âme d'un cloud engineer vous pouvez opter pour une installation dans le cloud google et **suivre le tutoriel pas à pas de Rémi** [ici](https://mc.ai/installer-sa-premiere-machine-avec-gpu-dans-le-cloud-2/). 


### Installation manuelle :  Installer Python 3.x (3.4, 3.5 ou 3.6) et pip (pip3)
**Pour Windows** : <https://www.python.org/downloads/windows/>

**Pour Mac** : <https://www.python.org/downloads/mac-osx/>

ou avec le terminal (sur Mac OS) 
```
brew install python3
brew install python3-pip
```

<a href ="https://brew.sh/index_fr"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Homebrew_logo.png">

### Installation manuelle (Mac OS) : Installer Homebrew sur votre Mac 
Si les commandes ci-dessus ne fonctionnent pas c'est que vous n'avez pas Homebrew ! 
Cliquer sur le logo ci-dessus et suivre le tutoriel d'installation. 


### Installation manuelle (via pip3) : Installer Jupyter 
Jupyter est une application web permettant de créer des notebooks, des fichiers mélangeant à la fois du texte (en syntaxe markdown), des images, des équations mathématiques et bien sur du code.

Lancer la commande suivante : 
```
 pip3 install jupyter
``` 

###  Installation manuelle : Installer les dépendances usuelles 
Lancer la commande suivante : 
```
pip3 install numpy matplotlib scipy pandas
```

### Vous n'avez pas pip 
Si les commande pip3 (respectivement pip pour python2) ne fonctionnent pas, pas de panique ! C'est que vous n'avez pas pip !  pip est un gestionnaire de paquets utilisé pour installer et gérer des paquets écrits en Python il va donc vous être fortement utile. 

##### Vous êtes sur Mac OS ou Linux
Pip3 c'est installé automatiquement via brew. Pour vérifier lancer la commande : 
```
pip3 list 
```
Cette commande renvoie la liste des paquets python installé sur votre ordinateur. 

##### Vous êtes sur Windows 
Sur Windows pip3 doit être dans le chemin que vous avez choisi durant votre installation de python, typiquement : 
```
C:\path\to\python\Scripts\pip3
```
Si vous ne savez pas ou ce trouve python utiliser 
```
where python
```


## Configurer son environnement de travail 
Maintenant que nos outils sont installés nous pouvons configurer proprement notre 'dossier de travail'. 
Ouvrez un terminal (pour ceux sur Mac OS et Linux). Si vous êtes sur Windows et que vous voulez vous exercer avec les commandes ci-dessous, vous pouvez télécharger [GitBash](https://gitforwindows.org/). 

### Rappel des commandes utiles sur terminal 

- pwd : ou je suis (dans quel dossier je suis) 
- cd *MonRepo* : changer de dossier (direcrtory)
- ls : lister les objets présents (fichier et dossier) dans le répertoire sélectionné
- mkdir *NewRepo* : créer un nouveau dossier de nom *NewRepo*  
- rm *UnFichier* : supprimer un fichier (attention avec cette commande!) 
- man *UneCommande* : afficher le manuel de la commande sélectionnée


### Créer son dossier de travail 

0 - Ouvrir un terminal (ou GitBash pour ceux sur Windows) 

1 - Créer un dossier (si non existant) *workspace* 

2 - Créer dans le dossier *workspace* un dossier *Cours* 

### Importer le repository de GitHub 

0 - Aller sur [la page d'accueil de ce git](https://github.com/bdallard/Simplon2k19)

1 - Appuyer sur le boutton vert *clone and download* (pour copier le lien du repo) 

2 - Cloner le repository (dans votre dossier Cours) avec la commande suivante : 
```
git clone https://github.com/bdallard/Simplon2k19
```

### Lancer Jupyter

Pour lancer jupyter, assurez vous de bien être positioné dans votre repo de travail (*Cours*) et lancer la commande suivante :  

```
jupyter notebook 
```

## Organisation du repo 
Comme énoncé au début ce repo servira de fil conducteur durant les cours.
Chaque dossier fait donc référence à une notion abrodée dans le cours. 

### Good lucks guys 
Vous pouvez maintenant commencer à travailler !