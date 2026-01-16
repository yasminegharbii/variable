# coding-variables

## Basic

---

## 1 — Corriger les déclarations de variables

Corrige les déclarations suivantes afin qu’elles soient valides en JavaScript :

```javascript
var 'animal' = 'monkey'; 
var 'monkey' = animal; 
var x= 15; 
var y =10; 
var var = 'y3ni?'; 
var true = false; 
var isTenEven = 10 % 2 = 0; 
 ```
 
## 2 — Créer et combiner des variables

Effectue les opérations suivantes dans la console :

 1. Crée une variable firstName et assigne-lui ton prénom

 2. Crée une variable lastName et assigne-lui ton nom

 3. Crée une variable fullName en utilisant firstName et lastName


 ## 3 — Fonction compteur

Écris une fonction appelée counter qui, à chaque invocation, retourne un nombre
qui est 1 de plus que lors de l’appel précédent.
PS :
Tu auras besoin d’une variable
Réfléchis à l’endroit où cette variable doit être déclarée


Exemple attendu :
```javascript
counter(); // => 1
counter(); // => 2
counter(); // => 3
```

 ## 4 — Déclaration et utilisation des variables

 1. Déclare une variable monAge sans lui assigner de valeur

 2. Affiche monAge

 3. Assigne une valeur à monAge

 4. Affiche monAge à nouveau

 5. Que se passe-t-il si on utilise une variable non déclarée ?


## 5 — Types de variables

Crée les variables suivantes puis affiche leur type avec typeof :

 1. Une variable nom contenant une chaîne de caractères

 2. Une variable estConnecte contenant true

 3. Une variable nombre contenant un nombre

 4. Affiche le type de chaque variable

## 6 — Calcul simple

Écris une fonction sumTwoNumbers qui prend deux nombres en paramètres après déclare une variable result

stocke la somme dans result et retourne result

Exemple attendu :

```javascript
sumTwoNumbers(3, 4); // => 7
```

## 7 — Calcul du prix avec taxe

Écris une fonction appelée priceWithTax qui : prend deux paramètres : price et tax

déclare une variable taxAmount qui contient le montant de la taxe

déclare une variable total qui contient le prix final

calcule le prix final en ajoutant la taxe au prix initial

retourne la variable total

```javascript
priceWithTax(100, 15); // => 115
priceWithTax(80, 20);  // => 96
```
