# developpement web ; javascript, web api fetch et json <!--Le dièse est l'équivalent des balises <h> en html-->

<u>B1 ESGI A+B INI - S2 - LYON</u> <!-- <u> souligne le texte-->

## <!-- double dièse <=> <h2>-->
 
Cours pre-TP CalculatriceJS

Sélctionner des Elements 

Par Id:

```bash
let element = document.getElementById("Id")
```

Modifier des éléments

Changer le texte :

```sh
Document.getElementById(« Id »).testContent = « Nouveau texte "
```
Ecouter et Reagir aux Evenemets

Ajouter un Ecouteur d'evenements : 

```sh
document.getElementId("monBouton").addEventListener("click", function (){

    alert("Bouton cliqué!")
});
```
 #le function() est une fonction anonyme, qui est un est passé en paramètre d'une autre fonction elle même anonyme.
#callback : fonction passée en paramètre d'une autre fonction.

Il exite trois façons de déclarer une chane ve caractère :

```sh
let str = "Hello World"
let str = 'Hello World'
let str = `Hello World`
```

Utiliser le triple egal pour comparer booléen 

```sh
elmt.value === "comp"
```

innerHTML = 
innerText = 

dom = la page dans le navigateur.

méthode de tableau :

```sh
.push() pour ajouter un élément au tableau
.pop() pour retirer une élément du tableau
.shift() pour changer un élément du tableau
.splice() 
.slice() 
```