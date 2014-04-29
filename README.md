# Incubart Live Template

## Installation

Avec PHPStorm fermé

### 1/ Live template PHPStorm
*/home/s-artois/.WebIde70/config/templates*


### 2/ Sauvegarder vos templates:
```bash
> mkdir ~/templateBckp
> mv ~/.WebIde70/config/templates/* ~/templateBckp
```


### 3/ Init git
```shell
> cd ~/.WebIde70/config/templates/
> git init
> git remote add origin git@github.com:sylvain-a/ShareLiveTemplate.git
> git pull
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

2 solutions :
En éditant directement les fichiers XMLs
Via l'éditeur (plus simple ?)

### 6/ Documentation des templates
  
  
GROUPE | ABBREVIATION | DESCRIPTION
--- | --- | ---
PHP | wrapq | wrap string with quote
USER | for | Simple for loop





