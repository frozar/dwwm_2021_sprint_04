# 🌕 Day02:

## Arrays: Level00

1. Déclarez un tableau vide.
2. Déclarez un tableau avec plus de 5 éléments.
3. Trouvez la longueur (length) de votre tableau.
4. Obtenez le premier élément, l'élément du milieu et le dernier élément du tableau.
5. Déclarez un tableau appelé `mixedDataTypes`, placez différents types de données dans le tableau et recherchez la longueur du tableau. La taille du tableau doit être supérieure à 5.
6. Déclarez un tableau nommé `itCompanies` et attribuez les valeurs initiales: `Facebook`, `Google`, `Microsoft`, `Apple`, `IBM`, `Oracle` et `Amazon`.
7. Affichez le tableau avec console.log().
8. Affichez le nombre d'élément qu'il y a dans le tableau `itCompanies`.
9. Affichez la première entreprise, l'entreprise du milieu de tableau et la dernière entreprise.
10. Affichez chaque entreprise.
11. Mettez le nom des entreprises en majuscule, un par un, et affichez-les
12. Affichez le tableau sous forme de phrase: "Facebook, Google, Microsoft, Apple, IBM, Oracle et Amazon sont de grandes entreprises d'IT".
13. Vérifiez si une certaine entreprise existe dans le tableau `itCompanies`. S'il existe, retournez le nom de l'entreprise sinon retournez "une société introuvable".
14. **(Facultatif)** Filtrez les entreprises qui ont plus d'un 'o' sans utiliser la méthode *filter*
15. Trier le tableau en utilisant la méthode sort()
16. Inversez le tableau en utilisant la méthode reverse()
17. Récupez dans un tableau les 3 premières entreprises du tableau `itCompanies` en utilisant la méthode slice()
18. Récupez dans un tableau les 3 dernières entreprises du tableau `itCompanies` en utilisant la méthode slice()
19. Récupez dans un tableau le milieu du tableau `itCompanies`, à savoir `["Apple"]` en utilisant la méthode slice()
20. Supprimez le premier élément du tableau `itCompanies` en utilisant la méthode splice()
21. Supprimez un élément au milieu du tableau `itCompanies` en utilisant la méthode splice()
22. Supprimez le dernier élément du tableau `itCompanies` en utilisant la méthode splice()
23. Supprimez tous les éléments du tableau `itCompanies`.

## Arrays: Level01

```js
// countries.js
const countries = [
    'USA',
    'Canada',
    'Denmark',
    'Algeria',
    'Tunisia',
    'Germany',
    'China',
    'Morocco',
    'Ireland',
    'Japan',
    'France'
]

// web_techs.js
const webTechs = [
  'HTML',
  'CSS',
  'JavaScript',
  'PHP',
  'MySQL',
  'Node',
  'Bootstrap'
]
```

1. Créez un fichier séparé countries.js et stockez le tableau countries dans ce fichier, créez un fichier distinct web_techs.js et stockez le tableau webTechs dans ce fichier. Accédez aux deux variables, `countries` et `webTechs`, depuis le fichier main.js. *Indice*: l'ordre d'inclusion des fichiers javascript dans le fichier html a une influence.

   
2. A partir du code suivant :

   ```js
   // main.js
   let text =
   'I love teaching and empowering people. I teach HTML, CSS, JS, VueJs, Laravel.'
   console.log(words)
   console.log(words.length)
   ```

   Supprimez les ponctuations dans la chaine de caractère `text`, changez la chaîne en tableau et comptez le nombre de mots dans le tableau.


   ```sh
   ["I", "love", "teaching", "and", "empowering", "people", "I", "teach", "HTML", "CSS", "JS", "VueJs", "Laravel"]
     
   13
   ```

3. Dans le panier suivant (shoppingCart), ajoutez, supprimez, modifiez des articles

   ```js
   const shoppingCart = ['Milk', 'Coffee', 'Tea', 'Honey']
   ```

   - ajoutez 'Meat' au début de votre panier s'il n'a pas déjà été ajouté.
   - ajoutez 'Sugar' à la fin de votre panier s'il n'a pas déjà été ajouté.
   - supprimez 'Honey' si vous êtes allergique au miel
   - modifier le thé en 'Green Tea'
4. Dans le tableau `countries`, vérifiez si `Morocco` existe dans le tableau et s'il existe, affichez "MOROCCO". S'il n'existe pas, ajoutez `Morocco` à la liste des pays.
5. Dans le tableau `webTechs`, vérifiez si `Sass` existe dans le tableau et s'il existe, affichez "Sass est un préprocesseur CSS". S'il n'existe pas, ajoutez `Sass` au tableau et affichez-le.
6. Concaténez les deux variables suivantes et stockez-les dans une variable fullStack.

    ```js
    const frontEnd = ['HTML', 'CSS', 'JS', 'VueJs', 'VueX']
    const backEnd = ['Node','Express', 'MongoDB']
  
    console.log(fullStack)
    ```

    ```sh
    ["HTML", "CSS", "JS", "VueJs", "VueX", "Node", "Express", "MongoDB"]
    ```
## Loops: Level00

1. Itérer de 0 à 10 en utilisant la boucle **for**, **while** et **do while**
2. Itérez 10 à 0 en utilisant la boucle **for**, **while** et **do while**
3. Créez et initialisez une variable `n` avec un entier positif. Itérer de 0 à `n` en utilisant la boucle **for**
4. Écrivez une boucle qui crée le modèle suivant à l'aide de console.log(): 

   ```js
       #
       ##
       ###
       ####
       #####
       ######
       #######
   ```

5. Utilisez une boucle pour affichez le modèle suivant à l'aide de console.log():

   ```sh
   0 x 0 = 0
   1 x 1 = 1
   2 x 2 = 4
   3 x 3 = 9
   4 x 4 = 16
   5 x 5 = 25
   6 x 6 = 36
   7 x 7 = 49
   8 x 8 = 64
   9 x 9 = 81
   10 x 10 = 100
   ```

6. Utilisez la boucle **for** pour parcourir de 0 à 100 et n'afficher que des nombres pairs
7. Utilisez la boucle **for** pour parcourir de 0 à 100 et n'afficher que les nombres impairs
8. **(Facultatif)** Utilisez la boucle **for** pour parcourir de 0 à 100 et n'afficher que les nombres premiers
9. Utilisez la boucle **for** pour parcourir de 0 à 100 et afficher la somme de tous les nombres.

    ```sh
    La somme de tous les nombres de 0 à 100 est 5050.
    ```

## Loops: Level01

1. Développez un script qui génère n'importe quel nombre de caractères aléatoire:

    ```sh
      fe3jo1gl124g
    ```

    ```sh
      xkqci4utda1lmbelpkm03rba
    ```
    
2. Ecrivez un script qui génère un numéro de couleur RGB aléatoire. 

    ```sh
    rgb(240,180,80)
    ```

## Functions: Level01

1. Déclarez une fonction _fullName_ qui affiche votre nom complet.
2. Déclarez une fonction _newFullName_ qui prend firstName, lastName comme paramètre et elle renvoie *return* votre nom complet.
3. Déclarez une fonction _addNumbers_ qui prend deux paramètres et elle renvoie *return* la somme.
4. Une aire d'un rectangle est calculée comme suit: _area = longueur x largeur_. Ecrivez une fonction qui calcule _areaOfRectangle_.
5. Le périmètre d'un rectangle est calculé comme suit: _perimeter = 2x (longueur + largeur)_. Ecrivez une fonction qui calcule _perimeterOfRectangle_.
6. L'aire d'un cercle est calculée comme suit: _area = π x r x r_. Ecrire une fonction qui calcule _areaOfCircle_
7. **(Facultatif)** La température en C° peut être convertie en F° en utilisant cette formule: _F° = (C° x 9/5) + 32_. Écrivez une fonction qui convertit C° en F°_convertCelciusToFahrenheit_.
8. **(Facultatif)** Math.max renvoie son plus grand argument. Écrivez une fonction findMax qui prend trois arguments et renvoie leur maximum sans utiliser la méthode Math.max.

    ```js
    console.log(findMax(0, 10, 5))
    10
    console.log(findMax(0, -10, -2))
    0
    ```
  ## Objects: Level01

1. Créez un objet vide appelé *chien*
2. Affichez l'objet *chien* sur la console
3. Ajoutez le nom, les pattes, la couleur, l'âge et les propriétés d'écorce pour l'objet *chien*. La propriété bark est une méthode qui renvoie _woof woof_
4. Obtenez le nom, les pattes, la couleur, l'âge et la valeur de l'écorce de l'objet *chien*
5. Définissez les nouvelles propriétés de l'objet *chien*: race, getDogInfo 

  ## Objects: Level02

1. Trouvez la personne qui possède de le plus compétences dans l'objet `users` ci-dessous.
2. Comptez les users connectés, comptez les users ayant plus de 50 points de l'objet suivant. 

   ```js
   const users = {
     Alex: {
       email: 'alex@alex.com',
       skills: ['HTML', 'CSS', 'JavaScript'],
       age: 20,
       isLoggedIn: false,
       points: 30
     },
     Asab: {
       email: 'asab@asab.com',
       skills: ['HTML', 'CSS', 'JavaScript', 'Redux', 'MongoDB', 'Express', 'React', 'Node'],
       age: 25,
       isLoggedIn: false,
       points: 50
     },
     Brook: {
       email: 'daniel@daniel.com',
       skills: ['HTML', 'CSS', 'JavaScript', 'React', 'Redux'],
       age: 30,
       isLoggedIn: true,
       points: 50
     },
     Daniel: {
       email: 'daniel@alex.com',
       skills: ['HTML', 'CSS', 'JavaScript', 'Python'],
       age: 20,
       isLoggedIn: false,
       points: 40
     },
     John: {
       email: 'john@john.com',
       skills: ['HTML', 'CSS', 'JavaScript', 'React', 'Redux', 'Node.js'],
       age: 20,
       isLoggedIn: true,
       points: 50
     },
     Thomas: {
       email: 'thomas@thomas.com',
       skills: ['HTML', 'CSS', 'JavaScript', 'React'],
       age: 20,
       isLoggedIn: false,
       points: 40
     },
     Paul: {
       email: 'paul@paul.com',
       skills: ['HTML', 'CSS', 'JavaScript', 'MongoDB', 'Express', 'React', 'Node'],
       age: 20,
       isLoggedIn: false,
       points: 40
     }
   }
   ```

3. Recherchez des personnes qui sont des développeurs MERN Stack à partir de l'objet users. MERN signifiant MongoDB, Express, React, Node.
4. Définissez votre nom dans l'objet users sans modifier l'objet utilisateur d'origine
5. Obtenez toutes les clés de l'objet users
6. Obtenez toutes les valeurs de l'objet users

🎉 CONGRATULATIONS ! 🎉

[<< Day 1](../day_01/day_01.md) | [Day 3 >>](../day_03/day_03.md)