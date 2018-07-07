Exercice 1 : 

Dans un dossier “Jaime_le_shell”, créer la suite de dossier et de fichier de sorte a ce que cela s’affiche : 

-->
pour réaliser cet exercice,  je suis d'abord allée sur mon bureau avec la commande : cd desktop .
une fois dans: Imac-de-Marine:desktop .
j'ai créée le dossier "Jaime-le_shell" avec la commande suivante : 
mkdir Jaime_le_shell .
j'ai accédée à ce nouveau dossier comme précédemment avec : 
cd Jaime_le_shell .
puis j'ai créée les fichiers avec > et les dossiers avec mkdir comme ceci: 
>test1 .
mkdir test2 .
mkdir test3 .
mkdir test4 .
>test5 .
mkdir test6 .
                                                                           
J'ai ensuite affiché les informations de manière détaillés de "Jaime_le_shell" avec la commande ls -l . (ls me permet de savoir ce qui se trouve dans un répertoire et -l me permet d'obtenir un listing ordonné sur une seule colonne, avec de nombreuses informations additionelles (droits, taille etc...) 

Exercice 2 :

Créer un dossier dans la racine qui porte de nom de “le_shell_cest_trop_cool!” :
mkdir le_shell_cest_trop_cool! .
                                                                                  
Exercice 3 :

Déplacer les les fichiers “test1” et “test5” dans le dossier que vous venez de créer, et copier des dossiers “test2” et “test6” dans le dossier que vous venez de créer.

Pour Déplacer un fichier il faut utiliser la commande mv . (mv pour deplacer suivi du nom du fichier suivi du nom de dossier ou l'on veut le deplacer) : 
mv test1 le_shell_cest_trop_cool! .
mv test2 le_shell_cest_trop_cool! .

Pour créer une copie d’un fichier, on utilise la commande cp . Il s'agit ici d'un dossier on utilise alors -r .  qui nous permet de sélectionner le dossier et ce qu'il contient, la commande s'écrit de la même manière que mv ( cp -r nom_fichier nom_dossier) :
cp -r test2 le_shell_cest_trop_cool! .
cp -r test6 le_shell_cest_trop_cool! .
