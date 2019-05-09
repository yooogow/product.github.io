# product-presentation

## Déscription générale
Ce template permet de présenter une idée d’application web prototypée avec https://www.figma.com. Ex: https://joz84.github.io/product.github.io/ . 
Elle contient 6 sections :
* Une barre de navigation
* Une bannière
* Un section présentant le concept
* Une section présentant une Prévisualisation du prototype Figma	
* Une section présentant l’équipe
* Un pied de page 

## Structure
Le template est structuré de la manière suivante:
* Un fichier index.html
* Un fichier style.css avec le style À NE PAS MODIFIER
* Un fichier custom.css regroupant les propriétés modifiable
* Un dossier « images » contenant toutes les images au format jpg sauf le logo au format png ( correspondant au format produit par freelogodesign.org ) 

## Import du template
Lien vers le projet Github: https://github.com/Joz84/product.github.io

![](../images-readme/)

Cliquer sur "Clone or Download" puis sur "Download ZIP »
Décompresser le fichier sur sa machine et l’ouvrir dans sublime text

## Personnaliser le texte
### Le contenu
L’ensemble du texte à modifier est dans le fichier index.html. Avec la configuration de base de sublime text ( theme: Monokai ) le texte modifiable a la couleur syntaxique BLANCHE. Il est déconseillé de toucher le reste, car cela risque de casser la structure globale du site. 

### La police
Pour personnaliser la police il faut tout d’abord choisir une police sur https://fonts.google.com.
Une fois la police choisie il faut cliquer sur le « + » en haut à droite de la fiche de la police choisie :

<img src="/images-readme/googlefonts1.png" width=700>

Un cadre Noir apparait en bas de la fenêtre. Il contient les instructions nécessaires pour importer la police dans son projet :

<img src="/images-readme/googlefonts2.png" width=700>

Dans index.html
Remplacer la ligne 9 :
```html

```
Dans custom.css
Modifier la ligne 3 pour changer la police des titres
Modifier la ligne 4 pour changer la police du texte
```css

```

## Personnaliser la couleur
### La couleur des titres et des cadres
Pour modifier la couleur des titres et des cadres, il faut modifier le fichier custom.css. Plus précisément, il faut modifier le code hexadécimal de la couleur dominante ( ex: #00898E ) aux ligne 7 et 8 :
```css

```

### Le fond de couleur ( dégradé ) de la présentation du Figma
Pour modifier la fond couleur, il faut encore une fois modifier le fichier custom.css. Plus précisément, les lignes 14, 15 et 16 qui sont issues de https://www.uigradients.com	

<img src="/images-readme/uigradients.png" width=700>

Cliquer sur « <> » ( Get css ) en haut à droite.

<img src="/images-readme/uigradients.png" width=700>

Cliquer sur « CLICK TO COPY » et coller le code à la place des lignes 14, 15 et 16 du fichier custom.css :
```css

```

## Personnaliser les images
Il est fortement conseillé de ne pas modifier le code pour changer les images. Il est conseillé de changer les images dans le dossier images. Pour que cela fonctionne il faut que les images et le MÊME NOM et la MÊME EXTENTION. Les extensions sont toutes jpg SAUF le logo qui est en png ( car cela correspond au format fourni par freelogodesign.org ).

## Inclure son la prévisualisation du prototype Figma
Pour inclure la prévisualisation du prototype Figma il faut se rendre sur https://www.figma.com sur son projet et lancer la présentation ( le triangle en haut à droite ) :

<img src="/images-readme/figma1.png" width=700>

Puis cliquer sur « Share Prototype » en haut à droite :

<img src="/images-readme/figma2.png" width=700>

Puis « Public embed »:

<img src="/images-readme/figm3.png" width=700>

Puis « Copy » et coller le code dans le fichier index.html à la place de la ligne 93 :
```html

```

## Personnaliser le nombre de membres de la team
Si l’équipe n’est pas constituée de 4 personnes il est possible d’ajouter/supprimer une fiche de présentation d’un membre dans la rubrique « L’équipe ». Pour cela il suffit de copier/supprimer le section comprise entre la ligne 141 et 151 du fichier index.html :
```html

```

