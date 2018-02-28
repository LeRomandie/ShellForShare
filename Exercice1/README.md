# Exercice 1
On va trouver tous les fichiers présents dans mon ordinateur

## Que va t'on faire
- Apprendre à se deplacer dans l'ordinateur 
  - La commande 'cd'
- Apprendre a créer un fichier/un dossier
  - Les commandes cat et mkdir 
- Apprendre a obtenir des informations sur les fichiers
  - La commande ls
- Apprendre a trouver un fichier
  - La commande find
  - Les expressions régulières
- Apprendre a supprimer un fichier/un dossier
  - La commande rm
- Apprendre a écrire dans un fichier
  - Encore la commande cat, mais pas que


## 1 Apprendre à se deplacer dans l'ordinateur 
### Place a la lecon
aller sur mon Bureau :
```console
foo@bar:~$ cd Desktop
```
Maintenant aller dans un repertoire
```console
foo@bar:~$ cd NomDeMonRepertoire
```
Revenir en arrière
```console
foo@bar:~$ cd ..
```
Revenir a la racine
```console
foo@bar:~$ cd
```
### Fil rouge
On va aller sur le bureau et on va créer un dossier qui contiendra toutes les données de cet exercice.
Go on va sur le bureau
```console
foo@bar:~$ cd Desktop/
```
hummmm mais je sais pas créer de dossier moi ?
ok passons a la lecon 2
## 2 Apprendre a créer un fichier/un dossier
### Place a la lecon
Créons un dossier ensemble
```console
foo@bar:~$ mkdir MonNouveauDossier
```

### Fil Rouge
On dire que ce dossier s'appelle MesPlusBellesMusiques
Créons un dossier pour mettre nos futurs résultats
```console
foo@bar:~$ mkdir MesPlusBellesMusiques
```
## 3 Apprendre a obtenir des informations sur les fichiers
### Place a la lecon
```console
foo@bar:~$ ls
```

```console
foo@bar:~$ ls -l
```

```console
foo@bar:~$ ls -ls
```
## 4 Apprendre a trouver un fichier

## 5 Apprendre a supprimer un fichier/un dossier
## 6 Apprendre a écrire dans un fichier


## Résultat final
```console
foo@bar:~$ find /Users/ddelalle/ -name '*.mp3' > liste_des_fichiers.txt
```
