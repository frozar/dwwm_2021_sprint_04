# 🌕 Day03:

## Higher Order Function


```js
const countries = ['Finland', 'Sweden', 'Denmark', 'Norway', 'IceLand']
const names = ['Max', 'Mathias', 'Elias', 'Brook']
const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
const products = [
  { product: 'banana', price: 3 },
  { product: 'mango', price: 6 },
  { product: 'potato', price: ' ' },
  { product: 'avocado', price: 8 },
  { product: 'coffee', price: 10 },
  { product: 'tea', price: '' },
]
```

1. Expliquez la différence entre **_forEach, map, filter, et reduce_**.
2. Définissez une fonction d'appel avant de les utiliser dans forEach, map, filter ou reduce.
3. Utilisez **_forEach_** pour console.log chaque pays du tableau des pays.
4. Utilisez **_forEach_** pour console.log chaque nom dans le tableau names.
5. Utilisez **_forEach_** pour console.log chaque nombre dans le tableau de nombres.
6. Utilisez **_map_** pour créer un nouveau tableau en modifiant chaque pays en majuscules dans le tableau des pays.
7. Utilisez **_map_** pour créer un tableau de longueur de pays à partir du tableau de pays.
8. Utilisez **_map_**  pour créer un nouveau tableau en changeant chaque nombre en racine carré _Math.sqrt()_ dans le tableau de nombres.
9. Utilisez **_map_** pour changer chaque nom en majuscules dans le tableau des noms
10. Utilisez **_filter_** pour filtrer les pays contenant **_land_**.
11. Utilisez **_filter_** pour filtrer les pays comportant six caractères.
12. Utilisez **_filter_** pour filtrer les pays contenant six lettres et plus dans le tableau des pays.
13. Utilisez **_filter_** pour filtrer le début du pays par 'E';
14. Utilisez **_filter_** pour filtrer uniquement les prix avec des valeurs.
15. Utilisez **_reduce_** pour additionner tous les nombres du tableau de nombres.
16. Utilisez **_reduce_** pour concaténer tous les pays et pour produire cette phrase: **_Estonia, Finland, Sweden, Denmark, Norway, and IceLand are north European countries_**
17. Expliquez la différence entre **_some_** et **_every_**
18. Utilisez **_some_** pour vérifier si la longueur de certains noms est supérieure à sept dans le tableau des noms
19. Utilisez **_every_**  pour vérifier si tous les pays contiennent le mot land
20. Expliquez la différence entre **_find_** et **_findIndex_**.
21. Utilisez **_find_** pour trouver le premier pays contenant seulement six lettres dans le tableau des pays.
22. Utilisez **_findIndex_** pour trouver la position du premier pays contenant seulement six lettres dans le tableau des pays.
23. Utilisez **_findIndex_** pour trouver la position de **_Norway_** si elle n'existe pas dans le tableau, vous obtiendrez -1.
24. Utilisez **_findIndex_** pour trouver la position de **_Russia_** si elle n'existe pas dans le tableau, vous obtiendrez -1.

## Sets and Maps

### Exercises:Level 1

```js
const a = {4, 5, 8, 9}
const b = {3, 4, 5, 7}
const countries = ['Finland', 'Sweden', 'Norway']
```

1. Créez un ensemble vide **set**
2. Créez un ensemble **set** contenant 0 à 10 en utilisant la boucle
3. Supprimez un élément d'un ensemble **set**
4. Effacez un ensemble **set**
5. Créez un ensemble **set** de 5 éléments de chaîne à partir du tableau
6. Créez un dictionnaire **map** des pays et du nombre de caractères d'un pays 

### Exercises:Level 2

1. Trouvez: a union b
2. Trouvez: a intersection b
3. Trouvez: a with b

## Destructuring and Spreading

### Exercises: Level 1

```js
const constants = [2.72, 3.14, 9.81, 37, 100]
const countries = ['Finland', 'Estonia', 'Sweden', 'Denmark', 'Norway']
const rectangle = {
  width: 20,
  height: 10,
  area: 200,
  perimeter: 60
}
const users = [
{
  name:'Brook',
  scores:75,
  skills:['HTM', 'CSS', 'JS'],
  age:16
},
{
  name:'Alex',
  scores:80,
  skills:['HTM', 'CSS', 'JS'],
  age:18
},
{
  name:'David',
  scores:75,
  skills:['HTM', 'CSS'],
  age:22
},
{
  name:'John',
  scores:85,
  skills:['HTML'],
  age:25
},
{
  name:'Sara',
  scores:95,
  skills:['HTM', 'CSS', 'JS'],
  age: 26
},
{
  name:'Martha',
  scores:80,
  skills:['HTM', 'CSS', 'JS'],
  age:18
},
{
  name:'Thomas',
  scores:90,
  skills:['HTM', 'CSS', 'JS'],
  age:20
}
]
```

1. Détruire et affecter les éléments du tableau de constantes à e, pi, gravity, humanBodyTemp, waterBoilingTemp.
2. Détruire et attribuer les éléments du tableau des pays à fin, est, sw, den, nor
3. Détruire l'objet rectangle par ses propriétés ou ses clés. 

### Exercises: Level 2

1. Parcourez le tableau des utilisateurs et obtenez toutes les clés de l'objet en utilisant la déstructuration.
2. Trouvez les personnes qui ont moins de deux compétences.

## Regular Expressions

### Exercises: Level 1

1. Ecrire un modèle qui identifie si une chaîne est une variable JavaScript valide.

    ```sh
    is_valid_variable('first_name') # True
    is_valid_variable('first-name') # False
    is_valid_variable('1first_name') # False
    is_valid_variable('firstname') # True
    ```

🎉 CONGRATULATIONS ! 🎉

[<< Day 2](../day_02/day_02.md) | [Day 4 >>](../day_04/day_04.md)