# 🌕 Day02: Is loading!

## Arrays --> Level00

1. Déclarez un tableau vide.
2. Déclarer un tableau avec plus de 5 éléments.
3. Trouvez la longueur (length) de votre tableau.
4. Obtenez le premier élément, l'élément du milieu et le dernier élément du tableau.
5. Déclarez un tableau appelé mixedDataTypes, placez différents types de données dans le tableau et recherchez la longueur du tableau. La taille du tableau doit être supérieure à 5
6. Déclarez un tableau nommé itCompanies et attribuez les valeurs initiales: Facebook, Google, Microsoft, Apple, IBM, Oracle et Amazon
7. Affichez le tableau avec console.log()
8. Affichez le nombre des entreprises dans le tableau.
9. Affichez la première entreprise, la moyenne et la dernière entreprise.
10. Affichez chaque entreprise.
11. Changez le nom de chaque entreprise en majuscules un par un et affichez-les
12. Affichez le tableau sous forme de phrase: Facebook, Google, Microsoft, Apple, IBM, Oracle et Amazon sont de grandes entreprises d'IT.
13. Vérifiez si une certaine entreprise existe dans le tableau itCompanies. S'il existe, retournez l'entreprise sinon retournez une société introuvable.
14. Filtrez les entreprises qui ont plus d'un 'o' sans utiliser la méthode *filter*
15. Trier le tableau en utilisant la méthode sort()
16. Inversez le tableau en utilisant la méthode reverse()
17. Découpez les 3 premières entreprises du tableau
18. Découpez les 3 dernières entreprises du tableau
19. Séparez (the middle) entreprise d'IT ou des entreprises à partir du tableau.
20. Supprimez la première entreprise d'IT à partir du tableau.
21. Supprimez (the middle) entreprise d'IT ou des entreprises à partir du tableau.
22. Supprimez la dernière entreprise d'IT à partir du tableau.
23. Supprimez toutes les entreprises d'IT.

## Arrays --> Level01

```js
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

1. Créez un fichier séparé countries.js et stockez le tableau countries dans ce fichier, créez un fichier distinct web_techs.js et stockez le tableau webTechs dans ce fichier. Accédez aux deux fichiers dans le fichier main.js

2. Supprimez d'abord toutes les ponctuations et changez la chaîne en tableau et comptez le nombre de mots dans le tableau.

    ```js
    let text =
    'I love teaching and empowering people. I teach HTML, CSS, JS, VueJs, Laravel.'
    console.log(words)
    console.log(words.length)
    ```

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
4. Dans le tableau 'countries', vérifiez si 'Morocco existe dans le tableau s'il existe, affichez 'MOROCCO'. S'il n'existe pas, ajoutez à la liste des pays.
5. Dans le tableau 'webTechs', vérifiez si 'Sass' existe dans le tableau et s'il existe, affichez «Sass est un préprocesseur CSS». S'il n'existe pas, ajoutez Sass au tableau et affichez-le.
6. Concaténez les deux variables suivantes et stockez-les dans une variable fullStack.

    ```js
    const frontEnd = ['HTML', 'CSS', 'JS', 'VueJs', 'VueX']
    const backEnd = ['Node','Express', 'MongoDB']
  
    console.log(fullStack)
    ```

    ```sh
    ["HTML", "CSS", "JS", "VueJs", "VueX", "Node", "Express", "MongoDB"]
    ```
## Loops --> Level00

1. Itérer de 0 à 10 en utilisant la boucle **for**, **while** et **do while**
2. Itérez 10 à 0 en utilisant la boucle **for**, **while** et **do while**
3. Itérer 0 à n en utilisant la boucle **for**
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

6. Utilisez une boucle pour affichez le modèle suivant à l'aide de console.log():

   ```sh
    i    i^2   i^3
    0    0     0
    1    1     1
    2    4     8
    3    9     27
    4    16    64
    5    25    125
    6    36    216
    7    49    343
    8    64    512
    9    81    729
    10   100   1000
   ```

7. Utilisez la boucle **for** pour parcourir de 0 à 100 et n'afficher que des nombres pairs
8. Utilisez la boucle **for** pour parcourir de 0 à 100 et n'afficher que les nombres impairs
9. Utilisez la boucle **for** pour parcourir de 0 à 100 et n'afficher que les nombres premiers
10. Utilisez la boucle **for** pour parcourir de 0 à 100 et afficher la somme de tous les nombres.

    ```sh
    La somme de tous les nombres de 0 à 100 est 5050.
    ```

11. Utilisez la boucle **for** pour itérer de 0 à 100 et afficher la somme de tous les nombres pairs et la somme de toutes les nombres impairs.

    ```sh
    La somme de tous les nombres pairs de 0 à 100 est 2550. Et la somme de tous les nombres impairs est 0 à 100 est 2500.
    ```

## Loops --> Level01



🎉 CONGRATULATIONS ! 🎉

[<< Day 1](./day_01/day_01.md) | [Day 3 >>](./day_03/day_03.md)