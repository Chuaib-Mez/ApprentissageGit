# Documentation de l'apprentissage Git et Github.

## initialiser un depot

```bash
git init
git remote add origin SSH_REPO #liaison entre notre dépot distant github et notre dossier
``` 

# Rédiger un commit (bonnes pratiques)

```
Titre du commit 

Description de celui-ci avec infos sur l'évolution du projet
```

## Envoyer un commit sur le dépot distant

```bash
git add .
git commit -m "Titre du commit" 
git push origin main 
#ou
git push -u origin main #upstream, permet de mémoriser la destination origin main
``` 

# Création d'une branche 

```bash
git checkout -b NOM_BRANCHE
``` 


Pour les bonnes pratiques, on va integrer la notion de revu de code. Pour cela, on va créer une branche, faire des modif, les envoyer sur le dépot distant, puis créer une pull request pour demander une revue de code.

