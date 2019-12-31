# Carte D'Identité Onset

## Introduction

>Modification du script original https://github.com/frederic2ec/onsetrp/tree/master/idcard
Modification du css en majorité.
Ajout de 4 types d’opacité pour le background (assets\img)
3 polices d'écriture sont utilisé dans ce package


## Code Samples

> Voici a quoi ressemble le projet initial puis sur la droite la nouvelle version :
![screenshot](https://i.ibb.co/GRf4ppm/Carte-identite.png)
![screenshot](https://i.ibb.co/mG5nmNW/new-CNI.png)

## Installation

> Clonez le dépôt  et balancez le dans votre dossier serveur.
si vous utilisez la base : https://github.com/frederic2ec/onsetrp
Collez ca dans package.json a la racine du dossier serveur dans la partie file.

```
        "idcard/assets/font/Cedarville-Cursive.ttf",
        "idcard/assets/font/Dusty.ttf",
        "idcard/assets/font/Monthoers.ttf",
        "idcard/assets/img/onset3.png"
```
Veillez a bien ajouter le 
```
        "idcard/assets/img/onset.png"
```
pour l'image 1,
```
        "idcard/assets/img/onset1.png"
```
pour l'image 2 etc..
Bien entendu, il faut les ajouter dans le package.json.
