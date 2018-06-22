---
title: "Onglet Acteurs"
description: "Documentation de l'onglet Acteurs pour RPG Maker VX Ace et MV."
og_image: "/assets/default_opengraph.png"
---

## Utilité de l'onglet Acteurs (ou Héros)

Cet onglet permet de configurer les données des acteurs. C'est le nom qui est donné dans RM aux personnages que le joueur contrôle. Il est possible de donner à chaque acteur des caractéristiques uniques.

## Configuration des acteurs

{{< figure src="/images/doc/bdd/acteur-MV.png" alt="Capture d'écran de l'onglet Acteurs de RPG Maker MV" caption="L'onglet Acteurs sous RPG Maker MV, en anglais" >}}

{{< figure src="/images/doc/bdd/acteur-Ace.png" alt="Capture d'écran de l'onglet Acteurs de RPG Maker VX Ace" caption="L'onglet Acteurs sous RPG Maker VX Ace, en français" >}}

Comme vous pouvez le constater, l'interface est exactement la même. 

### La partie de gauche

C'est ici qu'on peut sélectionner un acteur. Il est possible d'ajouter ou de supprimer des emplacements d'acteurs en appuyant sur le bouton `Changer maximum`. Par défaut MV ne propose que 4 acteurs alors que VX Ace en propose 10.

Il est possible de dupliquer un acteur en le copiant (`ctrl`+`C` puis `ctrl`+`V`) ou de le supprimer (`suppr`). On peut également faire ces opérations en effectuant un clic droit sur un emplacement d'acteur.

**Différences entre VX Ace et MV** : VX Ace permet de faire de la copie en masse d'acteurs. MV permet d'effectuer une recherche sur un mot ou une expression et va de lui-même sélectionner le premier acteur correspondant (raccourci : `ctrl`+`F`).

### La partie centrale

La partie centrale est divisée en trois blocs : les informations descriptives sur l'acteur, les images à associer et enfin son équipement de départ.

* Informations descriptives (bloc du haut) :

    * Le nom : c'est le nom de l'acteur tel qu'il sera affiché en jeu. Si le nom est trop long, il est possible qu'il en s'affiche pas correctement dans certaines fenêtres du jeu (fenêtre de combat et fenêtre de menu par exemple).
    * Le titre : c'est un nom alternatif donné à l'acteur. Il peut être plus long et devrait être plus descriptif. Ce nom alternatif n'apparait que dans le coin en haut à droite de la fenêtre de statut en jeu.
    * La classe : c'est la classe de l'acteur, à paramétrer dans l'[onglet Classes](). En fonction de la classe choisie, l'acteur aura accès à des compétences, des équipements précis et aura éventuellement des restrictions sur les objets qu'il peut utiliser. Pensez à bien choisir la classe avant de vous attaquer au bloc du bas.
    * Les niveaux : le *niveau initial* initial est le niveau de l'acteur au lancement du jeu (ou quand il rejoint l'équipe s'il ne fait aps partie de l'équipe initiale). Le *niveau maximal* est le niveau maximal que l'acteur peut atteindre. Une fois qu'il aura atteint ce niveau, il ne pourra plus gagner de points d'expérience. Vous ne pouvez enter que des valeurs comprises dans l'intervalle \[ 1 ; 99 \].

*À avancer plus tard.*
