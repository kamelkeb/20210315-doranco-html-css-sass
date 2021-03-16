# 20210315-doranco-html-css-sass
Exos et notes de cours:

15/03/2021

Exo 1:
Réaliser une page HTML, diposant d'une div en header, d'une deuxième div faisant office de panneau latéral. Cette deuxième div contiendra trois autres divs.
Chaque div devra avoir son propre background.
Le tout en respectant la maqu^ète à l'écran.

Exo 2:
Ajouter au centre de la page, une div de contenu (ou une section) qui contiendra 8 divs de mêmes tailles et mêmes couleurs.
Cette div centrale viendra se placer au centre de l'espace disponible.



TIPS:
- D'éviter les id si pas nécessaire
- Penser des balises (section ou div par exemple)
- Penser à l'attribution des responsabilités (quelle div pour quelle mise en forme, à quel étage spécifier les choses)
- Avoir un nommage cohérent
- Refactoring pour gégager ce qu'il y a de commun entre des éléments

Exo 3:
Pour rendre le layout responsive véritablement, faire en sorte que lorsque la taille la taille d'écran diminue en dessous 768px le menu latéral vienne se placer en tant
que tab bar

Exo 4:

Faire en sorte que lors du hover sur une entrée de menu, l'entrée vienne glisser légèrement vers la droite. 

Ressources:
GIT:
le fichier gitignore: https://www.youtube.com/watch?v=wQSiX9s90Uk

Flex: 
http://flexboxfroggy.com/


Remarques: 
1- Parfois besoin d'effectuer une opération arithmétique "dans" le CSS



Concernant l'opérateur de compas
.element-1, .element-2, .truc, a {
    background-color: pink; /*  <-- Ce style "S"  */
}

/*
OPTION 1: FAUSSSEEEE!!!!
Pour que ce style "S" s'applique à un élément "E", il faut qua la condition à gauche de la virgule
soit satisfaite par le dit élément "E" ET que la condition à droite de la virgule soit 
satisfaite par le même élément "E" au même moment

OPTION 2: CORRECTE!!!!
Pour que ce style "S" s'applique à un élément "E", il faut qua la condition à gauche de la virgule
soit satisfaite par le dit élément "E" OU ALORS que la condition à droite de la virgule soit 
satisfaite par le même élément "E" au même moment
*/
/*
condition globale = (condition1 OU condition2 OU condition3 OU condition4)

pour chaque élément pour lequel la condition globale s'avère vrai: le peindre en noir
*/


