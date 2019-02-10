# What did I learned today

## What is it

**wdilt** aims to:

- encourage me to **learn something new** every day
- see my progression **over time**
- become **better**

> As much as possible related to the **front-end development**

## Generate a Markdown Calendar

```JavaScript
class Calendar(year, month)
```

### Parameters

- `year` : the year of the **month you choose**
- `month` : the **month** you choose

### Run it

- **Create** a new `Calendar` with specific parameters
- Add `.fill()` **method**
- run `node app.js` in a **large terminal** to see the **results**

__Exemple:__

```JavaScript
const December2018 = new Calendar(2018, 12).fill();
```

> You can see the result in markdown below ⬇️

# Progression

## January

| 🗓 |        Su       |        Mo       |        Tu       |        We       |        Tu       |        Fr       |        Sa       |
| -- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- |
| W1 |                 |                 |[01](#2019-01-01)|[02](#2019-01-02)|[03](#2019-01-03)|[04](#2019-01-04)|[05](#2019-01-05)|
| W2 |[06](#2019-01-06)|[07](#2019-01-07)|[08](#2019-01-08)|[09](#2019-01-09)|[10](#2019-01-10)|[11](#2019-01-11)|[12](#2019-01-12)|
| W3 |[13](#2019-01-13)|[14](#2019-01-14)|[15](#2019-01-15)|[16](#2019-01-16)|[17](#2019-01-17)|[18](#2019-01-18)|[19](#2019-01-19)|
| W4 |[20](#2019-01-20)|[21](#2019-01-21)|[22](#2019-01-22)|[23](#2019-01-23)|[24](#2019-01-24)|[25](#2019-01-25)|[26](#2019-01-26)|
| W5 |[27](#2019-01-27)|[28](#2019-01-28)|[29](#2019-01-29)|[30](#2019-01-30)|[31](#2019-01-31)|                 |                 |
## February
| 🗓 |        Su       |        Mo       |        Tu       |        We       |        Tu       |        Fr       |        Sa       |
| -- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- |
| W1 |                 |                 |[01](#2019-01-01)|[02](#2019-01-02)|[03](#2019-01-03)|[04](#2019-01-04)|[05](#2019-01-05)|
| W2 |[06](#2019-01-06)|[07](#2019-01-07)|[08](#2019-01-08)|[09](#2019-01-09)|[10](#2019-01-10)|[11](#2019-01-11)|[12](#2019-01-12)|
| W3 |[13](#2019-01-13)|[14](#2019-01-14)|[15](#2019-01-15)|[16](#2019-01-16)|[17](#2019-01-17)|[18](#2019-01-18)|[19](#2019-01-19)|
| W4 |[20](#2019-01-20)|[21](#2019-01-21)|[22](#2019-01-22)|[23](#2019-01-23)|[24](#2019-01-24)|[25](#2019-01-25)|[26](#2019-01-26)|
| W5 |[27](#2019-01-27)|[28](#2019-01-28)|[29](#2019-01-29)|          
----

### 2019-01-19

Today I learned how to use [wdilt](https://github.com/blyndusk/wdilt)

----

### 2019-01-20


<!--git command-->
 Some GIT command :
 gst | ga/gaa | gc |  gp

<!--phpmyadmin and Mysql tips-->
 PhpMyadmin and mysql tips :
 I learned that it's possible to have in the same BDB tables with MyISAM  and another in InnoDB for better  performance 
 option + shift + entrée  ---> execute in phpmyadmin

<!--Aide memoire sql--->
- SELECT *
- FROM table
- WHERE condition
- GROUP BY expression
- HAVING condition
- { UNION | INTERSECT | EXCEPT }
- ORDER BY expression
- LIMIT count
- OFFSET start

----

### 2019-01-21
<!--ssh-->
Today I learned how to  connect SSH with shell : 

ssh root@example.com
ssh root@70.32.86.175
ssh domainuser@example.com

<!--Dump db--->
SQL of the day :

Producing a set of SQL statements that can be executed to reproduce the original database :

mysqldump -h [ ] -u [ ] -p [ ] > save.mysql
mysqldump --all-databases > dump.sql
mysqldump --databases db1 db2 db3 > dump.sql
mysqldump test > dump.sql

<!--{start|stop|restart|reload|force-reload|status}...-->
mysql.server  {start|stop|restart|reload|force-reload|status}

<!--Connection-->
 Mysql -u root -p / mysql -u root /
 Brew services start/restart ‘ex:mysql@5.7’ 
<!---Version-->
 -V for mysql 

 
----

### 2019-01-22

 Today I learned some svg form and tips with my boy Calou

 I also learned one way to build a db with paper and pen and tried mine 

Switch fonction 😎 
var answer = {a:0, e:0, i:0, o:0, u:0};
for (var i = 0; i < x.length; i++) {
  switch(x[i].toLowerCase()) {
    case 'a': answer.a++; break;
    case 'e': answer.e++; break;
    case 'i': answer.i++; break;
    case 'o': answer.o++; break;
    case 'u': answer.u++; break;
  }
}

----

### 2019-01-23
 SHELL of the day :

 Touch = créer un fichier
 mkdir / md  = créer un dossier
 cd .. = revenir de 1 dans le chemin | cd ../ = revenir a la racine
 Rm  = supprimer
 echo "ce que je veux écrire" >> "à la suite de quel fichier »
 echo "Ce que je veux écrire" > "En ecrasant le contenu du fichier"

 Some SQL :

 [- mysql -u root -p elevage] se connecter directement sur la base élevage

----

### 2019-01-24

Today I finished my first db with mysql in terminal 
  Php Today :
  var_dump() affiche le contenu d’une variable de manière brut , en précisant son type.
   echo , , , ;  
 The major differences to print are that echo accepts an argument list and doesn't have a return value.
 print_r for array
 $hi = printf('%y', ‘lol'); ===> echo $hi = 3
 $hi = sprintf('%y%y', « aaa","bbb') ===> echo  $hi = aaabbb

----

### 2019-01-25
Shell:

déplacer des fichiers (mv) ,( mv) sert aussi à renommer un fichier
copier des fichiers/dossiers (cp, rsync)
effacer des fichiers (rm)

Vimtutor sympa

php -S localhost:’8000’ // Serveur php

----

### 2019-01-26

----

### 2019-01-27

----

### 2019-01-28

SHELL :
cd .. (remonte d'un répertoire) cd ~ (identique à cd va dans le home de l'utilisateur) 
cd - (retourne au répertoire précédent)
cd ../ = revenir a la racine

----

### 2019-01-29

SHELL :
rm -rf /    détruit tout ce qu'il y a sur le ou les disques. 
PHP:le '\n' c'est le LF (Line Feed) et '\r' le CR (carriage return).

----

### 2019-01-30

SHELL:
?: remplace un caractère quelconque
*: remplace une chaîne de caractère quelconque

----

### 2019-01-31

Php:
in_array ( mixed $needle , array $haystack [, bool $strict = FALSE ] ) : bool
IP Version 4 publiques est arrivé officiellement à saturation le 3 février 2011.

----

### 2019-02-01

----

### 2019-02-02
Shell :

du -ks rep1 //espace disque occupé par l'arborescence du répertoire rep1 du -ks * //espace disque occupé par chaque sous-répertoire du répertoire courant 

----

### 2019-02-03

Shell :

ls avec l'option -i (ou - -inode) qui permet d'afficher le numéro d'inode dans le système de fichiers.
ln -s cible nom_du_lien 
Ln -s    //Create a symbolic link.

----

### 2019-02-04

----

### 2019-02-05

Shell:
which  //locate a program file in the user’s path
find rep1 -name file1.txt //Rechercher récursivement le fichier file1.txt dans le sous répertoire rep1 et ses sous-répertoire. 
Wihch Rechercher la commande  «  «  dans tous les répertoire de PATH. 

----

### 2019-02-06

Shell:
diff file1 file2 // Recherche ligne-à-ligne les différences entre les deux fichiers file1 et file2. 

----

### 2019-02-07

----

### 2019-02-08

----

### 2019-02-09

----

### 2019-02-10

----

