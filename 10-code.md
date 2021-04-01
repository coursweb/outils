---
layout: page
title: Editeurs de code
---

L'éditeur de code est un outil fondamental pour les métiers du web. Il existe un grand nombre d'éditeurs de code, ayant chacun ses particularités. Parmi les fonctionalités partagées par tous les éditeurs de code: 

- la colorisation de la syntaxe, pour faciliter la lecture et la détection d’erreurs.
- la suggestion automatique de termes propres au langage utilisé (HTML, CSS, JavaScript, etc).
- le  « rechercher remplacer » à l'échelle d'un projet ou dossier.
- le « rechercher remplacer » avec des « expressions régulières ».

![Quelques éditeurs de code...](img/code-editors.jpg)

* *[CotEditor](https://coteditor.com/)* - un éditeur simple, gratuit et open-source. Disponible pour MacOS uniquement.
* *[Sublime Text](https://www.sublimetext.com/)* - éditeur gratuit, le plus populaire en ce moment. Il existe [un grand nombre d'extensions](https://packagecontrol.io/) pour étendre ses fonctionalités. 
* *[Atom](https://atom.io/)* - éditeur gratuit et open source, très similaire à Sublime Text. Il existe également [des extensions](https://atom.io/packages).
* *[Brackets](http://brackets.io/)* - éditeur gratuit et open source, produit par Adobe.
* *[Visual Studio Code](https://code.visualstudio.com/)* - éditeur de code gratuit produit par Microsoft, disponible pour Windows, Mac et Linux. Inclut le support pour le versionnement Git. Le site [VSCodeCanDoThat.com](https://vscodecandothat.com/) donne des informations utiles.
* *[Coda](https://panic.com/coda/)* - éditeur avec des fonctions de prévisualisation. Prix: $99.
* *[Espresso](http://www.macrabbit.com/espresso/)* - éditeur avec des fonctions de prévisualisation du CSS. Prix: $75.
* *[PhpStorm](https://www.jetbrains.com/phpstorm/)* - éditeur spécialisé pour le langage PHP (utile pour le développement de thèmes WordPress, par exemple).


**L'inspecteur du navigateur** est un outil indispensable pour le développement d'interfaces web. Il permet l’analyse des éléments de mise en page d’un site, son chargement, son poids etc. Il est disponible dans les navigateurs majeurs (Firefox, Chrome, Safari). À noter que Firefox propose une "[version développeur](https://www.mozilla.org/fr/firefox/developer/)".

![L'inspecteur de Firefox permet une vue en 3D de la structure d'une page web](/img/FF-devtools-3d.jpg)

Dans Safari, il est nécessaire d'activer ces outils dans les préférences (sous *Avancées > Afficher le menu Développement...*).

Afin de pouvoir tester des sites sous Internet Explorer et Edge, Microsoft propose [des machines virtuelles Windows](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/) incluant ce navigateur (de IE8 à IE11 et Edge).


## Utiliser un éditeur de code

Exemples de rechercher-remplacer sur un document.

## Un outil de développement: Atom

- Configurer Atom pour un projet web: 
- configurer la synchro FTP
- configurer le "live reload"

### Configurer Atom pour un projet web

Quelques astuces pour la bonne utilisation d'Atom.

Note: pour bien fonctionner, Atom exige d'être placé dans le dossier Applications de MacOSX. Vous risquez de voir des erreurs si vous le lancez depuis un autre emplacement.

Aller dans Atom > Préférences: 
- Sous *Keybindings*, vous verrez la liste des raccourcis clavier.
- Sous *Packages*, vous verrez la liste des Packages (extensions) installés.
- Sous *Themes*, vous pouvez définir le thème de l'interface. Vous pouvez choisir un thème UI pour l’interface utilisateur, et un thème de Syntaxe.

- Ouvrir un projet: il est possible d'ouvrir un projet: avec la fonction *File > Open*, on peut choisir un dossier de projet (veiller à ne pas séléctionner de fichier). Cela permet de voir l’arborescence, utile quand on travaille sur un projet web.

Ajouter des fonctionnalités supplémentaires avec des Packages

- **autoclose-html** : pour fermer automatiquement les balises HTML.
- **webbox-color** : pour prévisualiser les couleurs CSS.
- **color-picker** : pour avoir un sélecteur de couleur.
- **linter** (et linter-csslint, linter-htmlhint) : pour détecter les erreurs de syntaxe dans votre code.
- **remote-sync** : pour permettre la syncronisation automatique avec un serveur FTP.
- **livereload** : pour recharger la fenêtre de navigateur dès que vous sauvez votre projet.
- **minimap** : pour avoir la vue miniature du code, commme dans Sublime Text.

Autres outils de développement : Sublime Text, Brackets, Espresso (particulièrement utile pour la prévisualisation du CSS), Coda, Dreamweaver, PHPStorm.

Utilitaires de développement : Grunt (task-runner), Composer...
