# Dofus Overlay - Dofus Tools

## Aide à la gestion du multi-comptes sur dofus

Passer d’un personnage à l’autre en plein combat ne devrait pas ressembler à un mini-jeu de gestion de fenêtres. Cet outil a justement été pensé pour simplifier les sessions multi-compte sur Dofus et rendre la navigation entre les comptes plus rapide, plus fluide et surtout moins pénible au quotidien.

Une version prête à l’emploi sera proposée prochainement pour les utilisateurs qui ne souhaitent pas mettre les mains dans Python, tout en laissant également l’accès aux sources pour ceux qui aiment comprendre ce qu’ils installent.

Même si l’objectif est simplement d’améliorer le confort de jeu, il reste important de rappeler qu’utiliser un programme externe demande toujours un minimum de vigilance. Vérifier les fichiers, consulter le code et télécharger uniquement depuis la source officielle reste la meilleure manière d’éviter les mauvaises surprises.

Le projet reprend l’idée générale de certains outils déjà connus de la communauté, notamment l’Organizer de DofusGuide, tout en apportant plusieurs ajustements, corrections et petits ajouts personnels. Si vous préférez utiliser une solution déjà bien installée dans l’écosystème Dofus plutôt qu’un projet partagé par un développeur random sur GitHub, leur application reste évidemment une alternative très correcte

## Installation:

- Téléchargez dofusOverlay.zip de la dernière release
- Dézipez le dossier
- Exécutez dofusOverlay.exe (il est possible que le logiciel ne soit pas reconnu par windows et que cela demande une autorisation)

## Fonctionnalités:

#### Toutes les fonctionnalités doivent respecter les CGU. Actuellement la seule fonctionnalité (macro click + tab sur la souris) est autorisée. [Lien forum dofus](https://www.dofus.com/fr/forum/1069-dofus/2404061-macros-autorise?page=2#entry13291455)

- appuyer sur tab (+shift) permet de passer à la page dofus suivante (précédente) (paramétrable dans le fichier ressources/config.json [option: next_win, prev_win]ou dans le menu déroulant pendant l'exécution)
- ne plus avoir le focus sur une page dofus fait disparaitre l'overlay (option: auto-disparition)
- clicker sur une image de l'overlay permet de changer de page dofus
- drag l'overlay permet de le déplacer
- Macro click + page suivante (equivalent à click+tab) (macro_clic_next_win)
- ctrl+click sur un personnage de l'overlay pour le sélectionner/désélectionner (Les personnages désélectionnés ne sont plus éligibles à l'affichage via tab)
- Appuyer sur f11 pour reorganiser les pages (option: reorganizer)
- Appuyer sur f13 pour focus sur la page dofus dernièrement selectionnée (option: focus_dofus)
- Actualisation manuelle via f4 pour éviter une boucle infini (option: actualise, auto-actualisation)
- Possibilité de mettre l'overlay à la verticale ou à l'horizontale (option: horizontal)
- Save les informations comme l'ordre ou les images.
- Invitation de tous les personnages dont une fenêtre est ouverte (cela pourrait enfreindre les CGU, je ne pense pas qu'il faille l'utiliser)

![](demo/demo.gif)

#### Nouveau visuel, sur le modèle de dofus guide

![](demo/visuel_overlay.png)

## Configurations:

Dans le fichier ressources/config.json, il est possible de faire quelques modifications pour personnaliser l'overlay

- il est possible de changer l'image associée à chaque personnage.
  Pour cela il faut cliquer sur la flèche lors de l'exécution puis sur le visage pour sélectionner une nouvelle icon ou ajouter une image dans ressource puis configurer le path dans information.json

![](demo/imagePerso.png)

- il est possible de changer l'assignation des touches pour certaines options

![](demo/touche.png)

- quelques autres modification comme la position de l'overlay et son opacité /!\ pas encore géré pour le nouvel overlay

![](demo/overlay.png)

## Bugs

-

## A ajouter:

-

## Bugs résolus

-

## Feature ajoutée

- Macro click + tab

Toutes images de personnage de [Dofus](https://www.dofus.com/fr/prehome) sont la propriété d'[Ankama](https://www.ankama.com/fr)
