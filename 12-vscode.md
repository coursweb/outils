---
layout: page
title: Visual Studio Code
permalink: vscode.html
---

## Raccourcis

Quelques raccourcis essentiels (sur clavier Mac suisse): 

- **Tab** : Indentation
- **shift + Tab** : Indentation à l'arrière
- **alt + Z** : Activer/Désactiver le retour automatique à la ligne.
- **cmd + shift + 7** : Mise en commentaire du code sélectionné.

- **cmd + F** : Rechercher (dans le document ouvert)
- **cmd + shift + F** : Rechercher dans les fichiers
- **cmd + shift + H** : Remplacer dans les fichiers

- **cmd + P** : Permet d'atteindre un fichier dans l'espace de travail.
- **cmd + shift + P** : Ouvre la *Palette de commandes*, qui permet d'exécuter diverses commandes (par exemple: *Mettre le document en forme*).

- **cmd +** : Zoom avant
- **cmd -** : Zoom arrière
- **cmd + B** : Activer/Désactiver le sidebar

## Extensions

Quelques extensions utiles:

- [LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) : permet d'activer un serveur local, avec rafraichissement automatique des pages dans le navigateur. 
- [LiveShare](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) : extension fournie par Microsoft, qui permet de collaborer à plusieurs sur un document.


## Divers

Comment visualiser votre site avec LiveServer sur un mobile (connecté sur le même réseau wifi).

Quand vous visualisez votre site, il aura une adresse comme ceci: http://127.0.0.1:5500/

Cette adresse est locale à votre ordinateur, cela ne fonctionnera pas depuis un autre appareil.

- Allez dans les *Préférences Système* de MacOS.
- Allez dans *Réseau* et sélectionnez le wifi. Vous aurez une info du type "Wifi est connecté à NomDuWifi et possède l’adresse IP 192.168.0.227."
- Cette adresse IP sera légèrement différente.

Sur le navigateur mobile, entrez cette IP avec http:// au début et :5500 à la fin, donc dans mon cas comme ceci: http://192.168.0.227:5500

Vous pourrez visualiser votre site en développement

## Modifier le settings.json

Certains réglages de VS Code doivent être faits dans le fichier `settings.json`. Pour y accéder: 

- lancer la **palette de commandes** avec `Affichage > Palette de commandes` ou `Maj+Cmd+P`.
- choisir : `>Préférences: Ouvrir les paramètres de l'utilisateur (JSON)`.
- cela ouvre un fichier de code dans lequel vous pouvez ajouter ou modifier les paramètres.
