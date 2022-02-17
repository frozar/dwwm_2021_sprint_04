# 🌕 Day05:

## Web Storages

### Exercises: Level 1

1. Enregistrez votre prénom, nom, âge, pays, ville dans votre navigateur avec **localStorage**.

### Exercises: Level 2

1. Créez un objet `student`. L'objet `student` aura un prénom, un nom, un âge, des compétences et un pays. Stockez l'objet `student` dans votre navigateur local **localStorage**.

## Promises


```js
const countriesAPI = 'https://restcountries.com/v3.1/all'
```

### Exercises: Level 1

1. A l'aide de la fonction `fetch()`, récupérez l'ensemble des pays depuis l'adresse `countriesAPI`. Pour chaque pays, affichez :
   - le nom du pays,
   - sa capitale,
   - ces langues,
   - sa population,
   - sa région.

### Exercises: Level 2

1. A l'aide de la fonction `fetch()`, récupérez l'ensemble des pays depuis l'adresse `countriesAPI`. Affichez les 10 pays les plus peuplés.
2. **(Facultatif)** A l'aide de la fonction `fetch()`, récupérez l'ensemble des pays depuis l'adresse `countriesAPI`. Comptez le nombre total de langues officielles utilisées dans le monde.

## Closures

Pour comprendre ce qu'est une closure, lisez [cet article](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8).

### Exercises: Level 1

1. Dans [la conclusion de l'article](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8#a82b) d'introduction aux closures, l'auteur décrit la closure `createCounter()`. Réimplémentez cette closure.
2. Dans [cette partie de l'article](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8#1daf) une fonction `createAdder()` est décrite. Créez une closure `createAdder(offset)` qui prend en paramètre un nombre `offset` et qui retourne une fonction `adder(b)`. La fonction `adder(b)` prend en paramètre un nombre `b` et retourne le nombre `offset + b`.
3. Créez une closure `createMultiplier(factor)` suivant la même démarche que la closure `createAdder(offset)`.

🎉 CONGRATULATIONS ! 🎉

[<< Day 4](../day_04/day_04.md) | [Day 6 >>](../day_06/day_06.md)