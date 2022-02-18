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
3. Utilisez **_forEach_** pour affichez (console.log) chaque pays du tableau des pays.
4. **(Facultatitf)** Utilisez **_forEach_** pour console.log chaque nom dans le tableau names.
5. **(Facultatitf)** Utilisez **_forEach_** pour console.log chaque nombre dans le tableau de nombres.
6. Utilisez **_map_** pour créer un nouveau tableau où chaque élément est le nom du pays en majuscule dans le tableau des pays.
7. Utilisez **_map_** pour créer un nouveau tableau où chaque élément est la longueur du pays à partir du tableau de pays.
8. **(Facultatitf)** Utilisez **_map_**  pour créer un nouveau tableau en calculant chaque nombre en racine carré _Math.sqrt()_ dans le tableau de nombres.
9. Utilisez **_map_** pour changer chaque nom en majuscules dans le tableau des noms
10. Utilisez **_filter_** pour filtrer les pays contenant **_land_**.
11. **(Facultatitf)** Utilisez **_filter_** pour filtrer les pays comportant exactement 6 caractères dans le tableau des pays.
12. Utilisez **_filter_** pour filtrer les pays contenant 6 lettres et plus dans le tableau des pays.
13. Utilisez **_filter_** pour filtrer les noms qui commence par 'E' dans le tableau names.
14. **(Facultatitf)** Utilisez **_filter_** pour filtrer uniquement les produits qui ont un prix (une valeur numérique) dans le tableau products.
15. Utilisez **_reduce_** pour additionner tous les nombres du tableau de nombres.
16. **(Facultatitf)** Utilisez **_reduce_** pour concaténer tous les pays et pour produire cette phrase: **_Estonia, Finland, Sweden, Denmark, Norway, and IceLand are north European countries_**
17. Expliquez la différence entre **_some_** et **_every_**
18. Utilisez **_some_** pour vérifier si la longueur de certains noms est supérieure à sept dans le tableau des noms.
19. Utilisez **_every_**  pour vérifier si tous les pays contiennent le mot **land**.
20. Expliquez la différence entre **_find_** et **_findIndex_**.
21. Utilisez **_find_** pour trouver le premier pays contenant seulement six lettres dans le tableau des pays.
22. Utilisez **_findIndex_** pour trouver la position du premier pays contenant seulement six lettres dans le tableau des pays.
23. **(Facultatitf)** Utilisez **_findIndex_** pour trouver la position de **_Norway_** dans le tableau countries; si elle n'existe pas dans le tableau, vous obtiendrez -1.
24. **(Facultatitf)** Utilisez **_findIndex_** pour trouver la position de **_Russia_** dans le tableau countries; si elle n'existe pas dans le tableau, vous obtiendrez -1.

## Sets and Maps

### Exercises: Level 1

```js
const countries = ['Finland', 'Iceland', 'Norway', 'Sweden',
                   'Sweden', 'Norway', 'IceLand', 'Finland']
```

1. Créez un ensemble vide [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
2. Créez un ensemble **Set** contenant les entiers de 0 à 10 en utilisant une boucle
3. Supprimez un élément d'un ensemble **Set**
4. Effacez un ensemble **Set**
5. **(Facultatif)** Créez un ensemble **Set** de 5 éléments de chaîne à partir du tableau `countries`
6. Créez un dictionnaire [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map) avec comme clés les pays et en valeur le nombre de caractères du pays associé

### Exercises: Level 2

```js
const a = {4, 5, 8, 9}
const b = {3, 4, 5, 7}
```

1. Calculer l'union de `a` et `b`
2. Calculer l'intersection entre `a` et `b`

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
```

1. Déstructurez et affectez les éléments du tableau `constants` dans les variables `e`, `pi`, `gravity`, `humanBodyTemp` et `waterBoilingTemp`.
2. Déstructurez et affectez les éléments du tableau `countries` dans les variables `fin`, `est`, `sw`, `den` et `nor`.
3. **(Facultatitf)** Déstructurez l'objet `rectangle` grâce à ses clés.

### Exercises: Level 2

```js
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

1. Parcourez le tableau des utilisateurs et obtenez toutes les clés de l'objet en utilisant la déstructuration.
2. Trouvez les personnes qui ont moins de deux compétences et mettez les dans un tableau.

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