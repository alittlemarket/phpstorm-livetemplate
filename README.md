# Incubart Live Template

## Installation
(PHPStorm fermé)

### 1/ Live template PHPStorm
*~/.WebIde70/config/templates*


### 2/ Sauvegarder vos templates:
```Shell
> mkdir ~/templateBckp
> mv ~/.WebIde70/config/templates/* ~/templateBckp
```


### 3/ Init GIT
```Shell
> cd ~/.WebIde70/config/templates/
> git init
> git remote add origin git@github.com:alittlemarket/phpstorm-livetemplate.git
> git pull origin master
```


### 4/ Vérifier
* Lancer PHPStorm
* Dans un fichier PHP, taper une phrase, sans guillemet, puis la sélectionner.
* Taper [CTRL] + [ALT] + [J]
* L'outil propose *wrapq* - *Wrap string with quote*.
* Taper [ENTER]
* La chaine est entourée par des guillemets doubles.
* Si ça n'est pas le cas, ou qu'une erreur survient, vérifier *~/.WebIde70/config/templates*, il doit contenir des fichiers XML

### 5/ Ajout des lives templates

Deux solutions :

1. Editer directement les fichiers XMLs
2. Via l'éditeur:
    1. [CTRL] + [ALT] + [s]
    2. Cliquer sur [Live Templates]
    3. Choisir la catégorie souhaitée
    4. Cliquer sur le [+] vert à droite

### 6/ Documentation des templates
  
  
GROUPE | ABBREVIATION | DESCRIPTION
--- | --- | ---
PHP | wrapq | wrap string with quote
PHP | dowhile | Insert a standard do while
PHP | swica | Insert a standard switch case
PHP | vdd | Insert a var_dump() followed by a die() method
USER | cd | Die with the file name and the line
USER | for | Simple for loop
USER | vd | Simple for var_dump


## Credits

![ALittleMarket](http://assets_orig.alittlemarket.com/image/header/logo.png)





