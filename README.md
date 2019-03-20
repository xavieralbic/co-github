# Introduction au travail collaboratif avec Git et GitHub

L'objectif est de proposer via une `Pull Request` l'ajout de vos prénom et nom à la liste présente dans le fichier `promotion.txt`.

## Étape 1 : créer un fork
Cliquez sur le bouton `Fork` en haut à droite de cette page afin de créer une copie du dépôt sur votre compte GitHub personnel. Puis rendez-vous sur la page de vos `repositories`, vous devrez y trouver une copie de ce projet sur votre GitHub.

## Étape 2 : récupérer son Fork en local
Sur votre machine, dans un terminal tapez la commande :
```
git clone <url de votre Fork GitHub>
```

L'URL de votre `Fork` est présente sur la page GitHub de votre `repository` (cliquez sur le bouton vert `Clone or download`).

## Étape 3 : modification du projet
Sur votre machine, vous devez créer une branche puis y modifier le firchier `promotion.txt` comme indiqué au début de ce document. Ajoutez la modification; faite un commit; puis publiez la modification sur votre `Fork`.

## Étape 4 : soumettre la proposition de modification
Retournez sur GitHub (cette page), allez dans l'onglet `Pull requests`. Cliquez sur `New pull request`.

> **⚠️ Information importante concernant la création de la pull request depuis GitHub**
>
> - le `base repository` doit être ce repository, la `base` doit être master
> - le `head repository` doit être votre repository et le `compare` doit être votre branche
