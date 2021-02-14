# 🌕 Day04:

## Console Object Methods

### Exercises:Level 1

1. Affichez le tableau des pays sous forme de tableau.
2. Affichez l'objet pays sous forme de tableau.
3. Utilisez _console.group()_ pour regrouper les journaux.

### Exercises:Level 2

1. 10 > 2 \* 10 utilisez _console.assert()_
2. Ecrivez un message d'avertissement en utilisant _console.warn()_
3. Écrivez un message d'erreur en utilisant _console.error()_

## Error handling

Voir la documentation sur [MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions/try...catch)

```js
try {
  // code that may throw an error
} catch (err) {
  // code to be executed if an error occurs
} finally {
  // code to be executed regardless of an error occurs or not
}
```

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

```js
let sqrt = 2 x 2
console.log(sqrt)

console.log('Hello, world")
```

```sh
Uncaught SyntaxError: Unexpected identifier
```

- TypeError: A type error has occurred

```js
let num = 10
console.log(num.toLowerCase())
```

```sh
Uncaught TypeError: num.toLowerCase is not a function
    at <anonymous>:2:17
```

## Classes

### Exercises Level 1

1. Créez une classe Animal. La classe aura les propriétés le nom (name), l'âge (age), la couleur (color), des jambes (legs) et créez différentes méthodes
2. Créez une classe enfant Dog et Cat à partir de la classe Animal. 

### Exercises Level 2

1. [Override] la méthode que vous créez dans la classe Animal.

## JSON

```js
const skills = ['HTML', 'CSS', 'JS', 'React','Node', 'Python']
let age = 250;
let isMarried = true
const student = {
  firstName:'Asabeneh',
  lastName:'Yetayehe',
  age:250,
  isMarried:true,
  skills:['HTML', 'CSS', 'JS', 'React','Node', 'Python', ]
}
const txt = `{
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
`
```

### Exercises Level 1

1. Changer le tableau des skills en JSON en utilisant _JSON.stringify()_

1. Stringifier la variable age.

1. Stringifier la variable isMarried.
   
1. Stringifier l'objet student.

### Exercises Level 2

1. Stringifier l'objet students seulement avec les propriétés: firstName, lastName et skills.

### Exercises Level 3

1. Parsez *txt* JSON en objet.
2. Trouvez l'utilisateur qui a de nombreuses compétences à partir de la variable stockée dans *txt*.

🎉 CONGRATULATIONS ! 🎉

[<< Day 3](../day_03/day_03.md) | [Day 5 >>](../day_05/day_05.md)