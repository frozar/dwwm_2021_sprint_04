# 🌕 Day04:

## Console Object Methods

```js
const countries = ['Finland', 'Sweden', 'Denmark', 'Norway', 'IceLand']
const user = {
  name:'Brook',
  scores:75,
  skills:['HTM', 'CSS', 'JS'],
  age:16
};
```

### Exercises: Level 1

1. Utilisez `console.table()` pour afficher le tableau des pays, `countries`, sous forme de tableau.
2. Utilisez `console.table()` pour afficher l'objet `user` sous forme de tableau.
3. Utilisez `console.group()` pour regrouper les affichages.

### Exercises: Level 2

1. Utilisez `console.assert()` sur l'expression `10 > ( 2 * 10 )` et affichez le message d'erreur "Cette expression n'est pas vraie".
2. Ecrivez le message d'avertissement "Fait gaffe !" en utilisant `console.warn()`.
3. Écrivez le message d'erreur "Cela ne fonctionne point !" en utilisant `console.error()`.

## Error handling

Lisez la documentation sur [MDN pour les instructions try...catch](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions/try...catch)

```js
try {
  // code that may throw an error
} catch (err) {
  // code to be executed if an error occurs
} finally {
  // code to be executed regardless of an error occurs or not
}
```

- Uncaught ReferenceError

Sur l'exemple suivant, utilisez les block `try`, `catch` pour afficher un message personnalisé lors du traitement de l'erreur `Uncaught ReferenceError`.

```js
let firstName = 'Aymane'
let fullName = firstName + ' ' + lastName

console.log(fullName)
```

```sh
Uncaught ReferenceError: lastName is not defined
    at <anonymous>:2:35
```

- SyntaxError: A syntax error has occurred

Sur l'exemple suivant, utilisez les block `try`, `catch` pour afficher un message personnalisé lors du traitement de l'erreur `Uncaught SyntaxError`.

```js
eval('hoo bar');
```

```sh
Uncaught SyntaxError: Unexpected identifier
```

- TypeError: A type error has occurred

Sur l'exemple suivant, utilisez les block `try`, `catch` pour afficher un message personnalisé lors du traitement de l'erreur `Uncaught TypeError`.

```js
let num = 10
console.log(num.toLowerCase())
```

```sh
Uncaught TypeError: num.toLowerCase is not a function
    at <anonymous>:2:17
```

<!-- ## Classes

### Exercises: Level 1

1. Créez une classe Animal. La classe aura les propriétés le nom (name), l'âge (age), la couleur (color), des jambes (legs) et créez différentes méthodes
2. Créez une classe enfant Dog et Cat à partir de la classe Animal. 

### Exercises: Level 2

1. [Override] la méthode que vous créez dans la classe Animal. -->

## JSON

```js
const skills = ['HTML', 'CSS', 'JS', 'React','Node', 'Python'];
let age = 250;
let isMarried = true;
const student = {
  firstName:'Asabeneh',
  lastName:'Yetayehe',
  age:250,
  isMarried:true,
  skills:['HTML', 'CSS', 'JS', 'React','Node', 'Python', ]
};
```

### Exercises: Level 1

1. A l'aide de la fonction `JSON.stringify()`, transformer le tableau `skills` en JSON.

2. A l'aide de la fonction `JSON.stringify()`, stringifier la variable `age`.

3. **(Facultatif)** A l'aide de la fonction `JSON.stringify()`, stringifier la variable `isMarried`.
   
4. A l'aide de la fonction `JSON.stringify()`, stringifier l'objet `student`.

### Exercises: Level 2

1.  A l'aide de la fonction `JSON.stringify()`, stringifier l'objet `student` en conservant uniquement les propriétés : `firstName`, `lastName` et `skills`.

### Exercises: Level 3

```js
const txt = {
    "Alex": {
        "email": "alex@alex.com",
        "skills": [
            "HTML",
            "CSS",
            "JavaScript"
        ],
        "age": 20,
        "isLoggedIn": false,
        "points": 30
    },
    "Asab": {
        "email": "asab@asab.com",
        "skills": [
            "HTML",
            "CSS",
            "JavaScript",
            "Redux",
            "MongoDB",
            "Express",
            "React",
            "Node"
        ],
        "age": 25,
        "isLoggedIn": false,
        "points": 50
    },
    "Brook": {
        "email": "daniel@daniel.com",
        "skills": [
            "HTML",
            "CSS",
            "JavaScript",
            "React",
            "Redux"
        ],
        "age": 30,
        "isLoggedIn": true,
        "points": 50
    },
    "Daniel": {
        "email": "daniel@alex.com",
        "skills": [
            "HTML",
            "CSS",
            "JavaScript",
            "Python"
        ],
        "age": 20,
        "isLoggedIn": false,
        "points": 40
    },
    "John": {
        "email": "john@john.com",
        "skills": [
            "HTML",
            "CSS",
            "JavaScript",
            "React",
            "Redux",
            "Node.js"
        ],
        "age": 20,
        "isLoggedIn": true,
        "points": 50
    },
    "Thomas": {
        "email": "thomas@thomas.com",
        "skills": [
            "HTML",
            "CSS",
            "JavaScript",
            "React"
        ],
        "age": 20,
        "isLoggedIn": false,
        "points": 40
    },
    "Paul": {
        "email": "paul@paul.com",
        "skills": [
            "HTML",
            "CSS",
            "JavaScript",
            "MongoDB",
            "Express",
            "React",
            "Node"
        ],
        "age": 20,
        "isLoggedIn": false,
        "points": 40
    }
}
```

1. A l'aide de la fonction `JSON.stringify()`, transformez l'objet `txt` en JSON.
2. **(Facultatif)** Trouvez l'utilisateur qui a le plus de compétences parmi les champs de personne défini dans `txt`.

🎉 CONGRATULATIONS ! 🎉

[<< Day 3](../day_03/day_03.md) | [Day 5 >>](../day_05/day_05.md)