# Retour sur le parcours Bapteme-correction-algo

## Commentaire global :

Je te félicite d’avoir fait les 4 exercices + l'exercice bonus qui était costaud :muscle: !
Tu as su comprendre la documentation fournie et l’appliquer à l’exercice en plus du cours 🤠.
Je te recommande juste de revoir les `typeOf` et les petites subtilités de `isNaN()` ;). Des petites choses, qui, j’en suis sûr, seront très vite assimilées 🙂.

Continue comme ça, tu es sur une **excellente voie** ! 🙂

### test1/2/3.js :

- nickel :+1:

### test4.js :

- C’est déjà très bien d’avoir comparé les longueurs mais n’oublie pas de vérifier aussi si la variable est de type `number` ou `string` ;).

```
var x = 1
x.length === undefined
var x = “123”
x.length === 3
```

### test5.js :

- isNaN(‘un’) retournera true mais isNaN(‘1’) retournera false. Essaye `sum([‘1’, 2, ‘3’, 4, ‘5’])` et regarde ce qu'il en ressort ;)
