# L'horloge de Berlin
Il s’agit d’un des grands katas extrêmement connus pour pratiquer les stratégies de tests.

Tuyau : il est même possible que vous deviez le faire lors d’un entretien d’embauche

Voici à quoi ressemble l’horloge :

![horloge](https://i.imgur.com/gNvO08C.png "horloge")

Il s’agit d’une série d’ampoules qui ont **deux états possibles : allumé ou éteint**.

**La grosse ampoule ronde du dessus est allumée les secondes paires et éteinte les secondes impaire**.

**Les deux lignes suivantes représentent les heures**. **La première ligne représente des blocs de 5 heures et est composée de 4 lampes rouges. La deuxième ligne représente des blocs de 1heure et est composée de 4 lampes rouges.**

**Les deux dernières lignes représentent les minutes**. **La ligne du dessus représente des bloque de 5 minutes et elle est composée de 11 lampes. Toutes les 3 lampes nous avons une lampe rouge et les autres sont jaunes. La ligne du bas est composée de 4 bloques jaunes représentant chacun une minute.**

L’exercice consiste à transformer l’heure digitale en heure de berlin.

> Étape 1 : implémenter la ligne des simples minutes
>
> Etape 2 : implémenter la ligne des blocs de 5 minutes
>
> Etape 3 : implémenter la ligne des heures simples
>
> Etape 4 : implémenter la ligne des blocs de 5 heures
>
> Etape 6 : implémenter la lampe des secondes
>
> Etape 7 : intégrer l’horloge entière

Vous allez former des paires et coder cet exercice en pair programming en suivant la méthode TDD.