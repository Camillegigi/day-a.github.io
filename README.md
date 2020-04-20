# Jour 1

## <a href="https://joz84.github.io/day-a.github.io/" target="_blanck">Demo</a>

Le 1er cours est disponible à l'adresse suivante :
<a href="https://docs.google.com/presentation/d/e/2PACX-1vTG02S_mq5pnkXvMSj36VNTqjMDypUAf-ql2YGz7HisuWGakCtsWRAQy0ajBHMnjC1S6y6WOJfqfuoa/pub?start=false&loop=false&delayms=60000" target="_blanck">
Cours 1</a>

La structure du code peut être retrouvée dans le fichier <a href="https://github.com/Joz84/day-a.github.io/blob/master/index.html" target="_blanck">index.html<a>.
  
Et l'ensemble des propriétés dans le fichier <a href="https://github.com/Joz84/day-a.github.io/blob/master/style.css" target="_blanck">style.css<a>

## Le fichier HTML
Créer un dossier "code".
Ouvrir le logiciel Sublime Text et faire glisser le dossier "code" à l'interieur.
Créer un fichier "index.html" en tapant clique droit sur le fichier "code" dans Sublime Text puis "add new file".

### Le squelette
Le squelette de la page HTML comprend deux parties. 
  o Une partie "HEAD" pour les informations nécéssaires mais non visibles (comme par exemple autoriser les carractères avec accent).
  o Une partie "BODY" qui contient tout le contenu visible de page.
Pour générer automatiquement le squelette taper ```html``` dans le fichier index.html.

<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>

#######


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title></title>
</head>
<body>

</body>
</html>

#########

<head>
  <meta charset="UTF-8">
  <title>Jour 1</title>
</head>


########


<body>
  <h1>Les Muffins de Grand Mère</h1>
</body>

#########


<body>
  <h1>Les Muffins de Grand Mère</h1>
  <h2>Fondants et croustillants</h2>
</body>

########

  <h3>Présentation</h3>
  <p>Les muffins sont de petits gâteaux individuels s'apparentant aux madeleines. Apparus au pays de Galles aux alentours du XIe siècle, ils sont très répandus dans les pays anglo-saxons, principalement aux États-Unis. Le principe caractéristique de fabrication des muffins consiste à préparer le mélange des ingrédients liquides et celui des ingrédients secs séparément, puis à mélanger rapidement et grossièrement les deux préparations. Contrairement aux cupcakes, les muffins n’ont jamais de glaçage.
  Les muffins sont traditionnellement sucrés. On peut les retrouver au chocolat (avec des pépites de chocolat) ou nature, mais il existe de nombreuses autres variétés : fraise, banane, framboise, orange, vanille, myrtille ou bleuets, etc.
  Il existe également des muffins salés, les English muffins ou muffins anglais, ressemblant à des sortes de petites crêpes très épaisses, faits à partir de pâte levée. Ces muffins salés sont quelquefois faits avec de la farine complète. Ils sont notamment employés comme base de la préparation des "œufs Bénédicte".</p>
  '
########

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
'
 ############

  <h4>Préparation</h4>

  <ol>
    <li>Etape 1 : Dans un premier saladier : mélanger la farine, le sucre, le sel, le sucre vanillé et la levure.</li>

    <li>Etape 2 : Dans un deuxième saladier : mélanger le lait, l'huile(ou beurre fondu) et les oeufs.</li>

    <li>Etape 3 : Verser le contenu du second saladier dans le premier et remuer jusqu'à obtenir une pâte plutôt lisse. Laissez tout de même quelques petits grumeaux.</li>

    <li>Etape 4 : Mettre au four 15 min à 180°C (thermostat 6)</li>
  </ol>

############

  <element attribut="valeur">text apparent à l'écran</element>
'
  <a href="https://www.marmiton.org/recettes/recette_muffins-tres-simples_166385.aspx" target="blank">En savoir plus</a>

#########

  Créer un dossier nommé "images"

  Télécharger une image d'un site de photo libre de droits, de qualité et gratuite.
  Exemple: Pexels ( https://www.pexels.com/fr-fr/ )
'
  Ranger la photo dans le dossier "images".

  <img src="images/muffin.jpg" alt="muffin">


###########
 Mise en page du text

  <p><strong>Les muffins</strong> sont de petits gâteaux individuels s'apparentant aux madeleines. Apparus au pays de Galles aux alentours du XIe siècle, ils sont très répandus dans les pays anglo-saxons, principalement aux États-Unis. Le principe caractéristique de fabrication des muffins consiste à préparer le mélange des ingrédients liquides et celui des ingrédients secs séparément, puis à mélanger rapidement et grossièrement les deux préparations. Contrairement aux cupcakes, les muffins n’ont jamais de glaçage.<br>
  Les muffins sont traditionnellement sucrés. On peut les retrouver au chocolat (avec des pépites de chocolat) ou nature, mais il existe de nombreuses autres variétés : fraise, banane, framboise, orange, vanille, myrtille ou bleuets, etc.<br>
  Il existe également des muffins salés, les English muffins ou muffins anglais, ressemblant à des sortes de petites crêpes très épaisses, faits à partir de pâte levée. Ces muffins salés sont quelquefois faits avec de la farine complète. Ils sont notamment employés comme base de la préparation des <i>"œufs Bénédicte"</i>.</p>
'

  <br>
  <a href="https://www.marmiton.org/recettes/recette_muffins-tres-simples_166385.aspx" target="blank">

####### image HTML sans CSS

####### CSS
#### lien entre les deux pages
link + tab
créer un fichier css et le nommer "style.css".

<head>
  [...]
  <link rel="stylesheet" href="style.css">
</head>
Attention : href="style.css" fait bien sur référence au fichier "style.css" et doit avoir le même nom.

# style.css
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

########

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

#######

body {
  background: pink;
  font-family: arial;
  text-align: center;
}

h4, ul, ol {
  text-align: left;
}

#####

img {
  width: 300px;
  height: 300px;
  object-fit: cover;
}

#####

a:hover {
  color: brown;
}

a, a:hover {
  text-decoration: none;
}


####### Police google
Google fonts (https://fonts.google.com/)

Aller sur le site google fonts.
Sélectionner une police en cliquant sur le petit "+" en fave du nom de la police.
Copier le code html de la forme :
  <link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">
Et le coller dans le code html au dessus de la ligne :
  <link rel="stylesheet" href="style.css">
Soit :

<head>
  <title>Jour 1</title>
  <link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>

Puis copier la propriété css de la forme :
font-family: 'Pacifico', cursive;
Et la coller dans le fichier css :


h1 {
  font-family: 'Pacifico', cursive;
  color: green;
  font-size: 32px;
}

h2, h3, h4 {
  font-family: 'Pacifico', cursive;
  font-size: 28px;
}

####### Vidéo

Aller sur Youtube et choisir une video (https://www.youtube.com/watch?v=fBuSNu2m3XA&feature=youtu.be)
Faire clique droit sur la vidéo.
Cliquer sur "< > Copier le code d'intégration".
Coller le code dans le fichier html la où vous souhaitez intégrer la vidéo :
Remarque : Il est possible de changer la taille de la vidéo grâce aux attributs "width" et "height".

<h3>La recette en vidéo</h3>
<iframe width="500" height="300" src="https://www.youtube.com/embed/fBuSNu2m3XA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# screenshot
