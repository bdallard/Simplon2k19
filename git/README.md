# Github Quickstart 

Ce README résume le support de cours Git de la séance S2-A. 

## Créer un nouveau dépot
Créez un nouveau dossier, ouvrez le et exécutez la commande
```
git init
```

## Cloner un dépôt
Créez une copie de votre dépôt local en exécutant la commande
```
git clone /path/to/repository
```

## Ajouter & valider du code dans un dépot
Pour un fichier utilisez 
```
git add <filename>
```
Pour ajouter tous les fichiers modifiés
```
git add *
```

### Pour valider vos changements, utilisez
```
git commit -m "Message de validation"
```

## Envoyer des changements sur une branche 
Pour envoyer vos changement à votre dépôt distant, exécutez la commande
```
git push origin master
```

## Les branches 
Les branches sont utilisées pour développer des fonctionnalités isolées des autres. La branche master est la branche par défaut quand vous créez un dépôt. Utilisez les autres branches pour le développement et fusionnez ensuite à la branche principale quand vous avez fini.

### Créer une branche sur votre dépot 
Pour créer une nouvelle branche nommée "feature_x" et passer dessus pour l'utiliser
```
git checkout -b feature_x
```

### Retourner sur votre branche principale
```
git checkout master
```

### supprimer la branche
```
git branch -d feature_x
```
**Attention une branche n'est pas disponible pour les autres tant que vous ne l'aurez pas envoyée vers votre dépôt distant**

### Git Kesako
Pour ceux qui n'arrivent pas à pull parce qu'ils ont fait des modif dans le repo, lancer la commande : 
```
git stash
git pull
git stash pop
```
