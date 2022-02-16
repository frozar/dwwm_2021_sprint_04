# 🌕 Day07

## Sensibilisation au formattage des champs d'input

Dans le développement Front End, vous pouvez être confronté à des situations où vous voulez que les champs d'`input` respectent un format donné.

Par exemple, lorsque vous demandez un numéro de téléphone à un utilisateur, à la fin de sa saisie, il s'attend à voir un champ sous cette forme :

```
Téléphone : 02 62 12 34 56
```

Cette affichage peut sembler satisfaisant, mais dans le cas où vous souhaitez que le numéro rentré par l'utilisateur soit utilisable n'importe où dans le monde, vous souhaitez que l'indicatif du numéro de téléphone apparaisse dans le champ de saisie :

```
Téléphone : (+262) 262 12 34 56
```

Ce formattage est correcte dans le cas d'un numéro de l'île de la Réunion, mais dans le cas d'un numéro de métropole, l'utilisateur s'attend plutôt au formattage suivant :

```
Téléphone : (+33) 6 12 34 56 78
```

## Mini projet : numéro de téléphone

Réalisez une application web qui propose à un utilisateur de rentrer son numéro de téléphone. L'utilisateur doit pouvoir préciser s'il souhaite entrer un numéro de téléphone de l'île de la Réunion ou de France métropolitaine. Suivant ce choix, l'indicatif adéquat doit apparaître dans le champ d'input. Cette indicatif ne pourra pas être supprimé par l'utilisateur.

Lorsque l'utilisateur saisi son numéro de téléphone dans le champ d'input, celui-ci doit se formatter lors de la saisi. Par exemple, si l'utilisateur a choisi d'entrer un numéro de téléphone de France métropolitaine, lorsqu'il entrera le premier chiffre de son numéro, il doit y avoir un espace avant le curseur (le curseur étant représanté par une barre vertical (pipe) sur l'illustration ci-dessous) :
```
Téléphone : (+33) |
```

Après avoir saisi le premier chiffre, pour respecter le format, il doit à nouveau avoir un espace devant le curseur :
```
Téléphone : (+33) 6 |
```

Lorsque l'utilisateur saisi son deuxième chiffre, pour respecter le format, il n'y a pas d'espace devant le curseur :
```
Téléphone : (+33) 6 1|
```

Enfin, lorsqu'il saisit son troisième chiffre :
```
Téléphone : (+33) 6 12 |
```

Ainsi de suite pour l'enemble de la saisie.

Dans le cas d'un numéro de l'île de la Réunion, l'utilisateur ne pourra pas renseigner plus de 9 chiffres, et pour un numéro de la France métropolitaine, pas plus de 9 chiffres également.

Lors de la saisie, l'utiliteur pourra bien sûr supprimer un ou plusieurs chiffres dans le cas où il s'est trompé.

## Mini projet : numéro de carte vitale

Les numéros présents sur une carte ont tous une signification : le sexe, l'année, la commune, etc...

La disposition de ces chiffres respecte aussi un format bien précis, à savoir :
```
x xx xx xx xxx xxx xx
```

Les 13 premiers chiffres de la carte vitale ont un signification pour rapport à la naissance d'une personne, mais les deux derniers chiffres désignent la clé de la carte vitale. Cette clé est le résultat d'un calcul réalisé sur les 13 premiers chiffres de la carte.

Renseignez vous sur le calcul de cette clé grâce à [cette page](http://serge.mehl.free.fr/exos/cle_INSEE.html).

Réalisez une application web qui permet à un utilisateur de renseigner son numéro de carte vitale. Cette application comportera deux champ d'input.

Le premier champ d'input sera l'endroit où l'utilisateur pourra renseigner son numéro de carte vitale. La saisi de ces 13 premiers chiffres doit respecter le formattage de la carte vitale, de façon similaire à ce qui est détaillé dans le projet précédent, `numéro de téléphone`.

Le deuxième champ d'input est un champ désactivé où la clé sera affichée une fois que l'utilisateur aura saisi les 13 premiers chiffres de sa carte vitale.

🎉 CONGRATULATIONS ! 🎉

[<< Day 6](../day_06/day_06.md) | [Day 8 >>](../day_08/day_08.md)
