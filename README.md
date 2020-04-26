# Jour 1

## <a href="https://joz84.github.io/day-a.github.io/" target="_blanck">Demo</a>

Le 1er cours est disponible à l'adresse suivante :
<a href="https://docs.google.com/presentation/d/e/2PACX-1vTG02S_mq5pnkXvMSj36VNTqjMDypUAf-ql2YGz7HisuWGakCtsWRAQy0ajBHMnjC1S6y6WOJfqfuoa/pub?start=false&loop=false&delayms=60000" target="_blanck">
Cours 1</a>

La structure du code peut être retrouvée dans le fichier <a href="https://github.com/Joz84/day-a.github.io/blob/master/index.html" target="_blanck">index.html<a>.
  
Et l'ensemble des propriétés dans le fichier <a href="https://github.com/Joz84/day-a.github.io/blob/master/style.css" target="_blanck">style.css<a>

## Le fichier HTML
* Créer un dossier "code".
* Ouvrir le logiciel Sublime Text et faire glisser le dossier "code" à l'interieur.
* Créer un nouveau fichier en tapant clique droit sur le dossier "code" apparent sur la partie gauche dans Sublime Text puis cliquer sur "new file".
* Sauvegarder le fichier en cliquant sur "File" puis "Save". Taper le nom du fichier "index.html" (attention, petite liste des erreures classique : "index.html" est sans "i" majuscule, sans "e" à la fin et l'extenstion est bien "html" et pas "htlm"). Assurer vous d'être bien dans le dossier "code" avant de sauvegarder.  

### Le squelette
Le squelette de la page HTML comprend deux parties. 
  * Une partie "HEAD" pour les informations nécéssaires mais non visibles (comme par exemple autoriser les carractères avec accent).
  * Une partie "BODY" qui contient tout le contenu visible de page.
Pour générer automatiquement le squelette taper ```html``` dans le fichier index.html puis la touche "tabulations".

```html
<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
```

Pour pouvoir utiliser des carractères avec accent il faut rajouter la la ligne ```<meta charset="UTF-8">``` dans la partie "HEAD" :

```html
<head>
  <meta charset="UTF-8">
  <title></title>
</head>
...
```

Pour personnaliser le nom présent dans l'onglet du navigateur on doit spécifier un "title"

```html
<head>
  <meta charset="UTF-8">
  <title>Jour 1</title>
</head>
```

### Le titre principal

Pour écrire un titre dans la page il faut utiliser la balise "h1" (header 1).

```html
<body>
  <h1>Les Muffins de Grand Mère</h1>
</body>
```
### Les sous-titres
De la même manière, si l'on souhaite ajouter un sous-titre on utilise la balise "h2" (header 2).
Ils existent 6 niveaux de sous-titres.

```html
<body>
  <h1>Les Muffins de Grand Mère</h1>
  <h2>Fondants et croustillants</h2>
</body>
```
### Les paragraphes
On peut également ajouter un paragraphe grâce à la balise "p".

```html
<h3>Présentation</h3>
<p>Les muffins sont de petits gâteaux individuels s'apparentant aux madeleines. Apparus au pays de Galles aux alentours du XIe siècle, ils sont très répandus dans les pays anglo-saxons, principalement aux États-Unis. Le principe caractéristique de fabrication des muffins consiste à préparer le mélange des ingrédients liquides et celui des ingrédients secs séparément, puis à mélanger rapidement et grossièrement les deux préparations. Contrairement aux cupcakes, les muffins n’ont jamais de glaçage.
  Les muffins sont traditionnellement sucrés. On peut les retrouver au chocolat (avec des pépites de chocolat) ou nature, mais il existe de nombreuses autres variétés : fraise, banane, framboise, orange, vanille, myrtille ou bleuets, etc.
  Il existe également des muffins salés, les English muffins ou muffins anglais, ressemblant à des sortes de petites crêpes très épaisses, faits à partir de pâte levée. Ces muffins salés sont quelquefois faits avec de la farine complète. Ils sont notamment employés comme base de la préparation des "œufs Bénédicte".
</p>
```

### Les listes non-ordonnées (Unordered List)

La balise pour créer une liste non ordonnée est la balise "ul". Une liste est composée de plusieurs items, il faut donc créer un balise "li" (List Item) par item.

```html
<h4>Ingredients</h4>

<ul>
  <li>280 g de farine</li>
  <li>2 oeufs</li>
  <li>100 g de sucre</li>
  <li>150 ml de lait</li>
  <li>80 g de beurre (ou 8 cuillères à soupe d'huile)</li>
  <li>1 sachet de levure chimique</li>
  <li>1 sachet de sucre vanillé</li>
  <li>1 pincée de sel</li>
  <li>Cannelle</li>
  <li>Extrait de vanille</li>
</ul>
```
### Les listes ordonnées (Ordered List)

Ils existent aussi des listes ordonnées. La balise associée est la balise "ol".

```html
<h4>Préparation</h4>

<ol>
  <li>Etape 1 : Dans un premier saladier : mélanger la farine, le sucre, le sel, le sucre vanillé et la levure.</li>
  <li>Etape 2 : Dans un deuxième saladier : mélanger le lait, l'huile(ou beurre fondu) et les oeufs.</li>
  <li>Etape 3 : Verser le contenu du second saladier dans le premier et remuer jusqu'à obtenir une pâte plutôt lisse. Laissez tout de même quelques petits grumeaux.</li>
  <li>Etape 4 : Mettre au four 15 min à 180°C (thermostat 6)</li>
</ol>
```
### La structure d'une balise 

Une balise peut être constituée de 4 parties :
* Le tag (ex: h1)
* Les attributs (ex: width)
* La valeur associée (ex: 200px)
* Le text apparent

```html
<tag attribut="valeur">text apparent à l'écran</tag>
```

### Les liens de page en page

La balise pour lier deux pages est la balise "a".

```html
<a href="https://www.marmiton.org/recettes/recette_muffins-tres-simples_166385.aspx" target="blank">En savoir plus</a>
```
### Les images

Créer un dossier nommé "images".

Télécharger une image d'un site de photo libre de droits, de qualité et gratuite.
Exemple: Pexels ( https://www.pexels.com/fr-fr/ )

Ranger la photo dans le dossier "images".

Renommer l'image avec un nom simple, sans accent et sans espace (ex: "muffin.jpg").

La balise pour insérer une image est la balise "img", elle contient au moins un attribut, l'attribut "src" ( pour "source"). La valeur de cet attribut doit être le chemin relatif de l'image. Dans notre exemple cela est "images/muffin.jpg". 

```html
<img src="images/muffin.jpg" alt="muffin">
```
On peut egalement ajouter l'attribut "alt" ( pour "alternative"). la valeur de cet attribut est un text décrivant au mieux l'image. Dans notre exemple "muffin". l'attribut "alt" a trois applications :
* Le text s'affiche sur la page si le navigateur ne trouve pas l'image.
* Les applications pour aveugles qui lisent la page HTML notifiront qu'il y a une image et ce quelle représente.
* Mettre une description pertinante améliore le référencement.

### Mise en page du text

```html
<p><strong>Les muffins</strong> sont de petits gâteaux individuels s'apparentant aux madeleines. Apparus au pays de Galles aux alentours du XIe siècle, ils sont très répandus dans les pays anglo-saxons, principalement aux États-Unis. Le principe caractéristique de fabrication des muffins consiste à préparer le mélange des ingrédients liquides et celui des ingrédients secs séparément, puis à mélanger rapidement et grossièrement les deux préparations. Contrairement aux cupcakes, les muffins n’ont jamais de glaçage.
<br>
Les muffins sont traditionnellement sucrés. On peut les retrouver au chocolat (avec des pépites de chocolat) ou nature, mais il existe de nombreuses autres variétés : fraise, banane, framboise, orange, vanille, myrtille ou bleuets, etc.
<br>
Il existe également des muffins salés, les English muffins ou muffins anglais, ressemblant à des sortes de petites crêpes très épaisses, faits à partir de pâte levée. Ces muffins salés sont quelquefois faits avec de la farine complète. Ils sont notamment employés comme base de la préparation des 
<i>"œufs Bénédicte"</i>.
</p>
```

```html
<br>
<a href="https://www.marmiton.org/recettes/recette_muffins-tres-simples_166385.aspx" target="blank">
```
####### image HTML sans CSS

####### CSS
#### lien entre les deux pages
```link``` + tab
créer un fichier css et le nommer "style.css".

```html
<head>
  [...]
  <link rel="stylesheet" href="style.css">
</head>
Attention : href="style.css" fait bien sur référence au fichier "style.css" et doit avoir le même nom.
```

# style.css
```css
h1 {
  color: green;
  font-size: 32px;
  background: pink;
  font-family: arial;
}

h2, h3, h4 {
  font-size: 28px;
  background: pink;
  font-family: arial;
}

p, ul, ol {
  font-size: 20px;
}
```

########
    
```css
body {
  background: pink;
  font-family: arial;
}

h1 {
  color: green;
  font-size: 32px;
}

h2, h3, h4 {
  font-size: 28px;
}
```

#######

```css
body {
  background: pink;
  font-family: arial;
  text-align: center;
}

h4, ul, ol {
  text-align: left;
}
```

#####

```css
img {
  width: 300px;
  height: 300px;
  object-fit: cover;
}
```

#####

```css
a:hover {
  color: brown;
}

a, a:hover {
  text-decoration: none;
}
```

## Police google
Google fonts (https://fonts.google.com/)

Aller sur le site google fonts.
Sélectionner une police en cliquant sur le petit "+" en fave du nom de la police.
Copier le code html de la forme ```<link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">``` et le coller dans le code html au dessus de la ligne ```<link rel="stylesheet" href="style.css">```
Soit :

```html
<head>
  <title>Jour 1</title>
  <link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
```

Puis copier la propriété css de la forme ```font-family: 'Pacifico', cursive;``` et la coller dans le fichier css :

```css
h1 {
  font-family: 'Pacifico', cursive;
  color: green;
  font-size: 32px;
}

h2, h3, h4 {
  font-family: 'Pacifico', cursive;
  font-size: 28px;
}
```

## Vidéo

Aller sur Youtube et choisir une video (https://www.youtube.com/watch?v=fBuSNu2m3XA&feature=youtu.be)
Faire clique droit sur la vidéo.
Cliquer sur "< > Copier le code d'intégration".
Coller le code dans le fichier html la où vous souhaitez intégrer la vidéo :
Remarque : Il est possible de changer la taille de la vidéo grâce aux attributs "width" et "height".

```html
<h3>La recette en vidéo</h3>
<iframe width="500" height="300" src="https://www.youtube.com/embed/fBuSNu2m3XA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

### screenshot
