# git-commands
Un petit lexique perso de Git

# Lexique

git config --global user.email "e-mail" = pour dire qui on est à Git


git init "Nom du dossier" = c'est pour dire que ça c'est un dossier Git

git remote add origin "Lien GitHub" = pour lier son dossier PC à GitHub (au master)

git remote add fork "Lien GitHub" = pour lier sa branche GitHub à son dossier PC

git remote -v = pour voir le listing des remote

git branch "NomDeLaBranche" = créer une branche

Faire git branch -a pour afficher la liste des branches sur le serveur

git pull origin master = pour tirer sur son PC les dossiers et fichiers de GitHub

git pull origin "Nom de la branche" = pour tirer sur son PC les dossiers et fichiers de GitHub

git add . = ajouter toutes les modifs qu'on a fait dans une boîte (on peut également git add "Nom du fichier" si on veut seulement ajouter un fichier)

git commit -m "Nom du commit" = créer un commit(enregistrement), donne un nom à sa boite

git push fork master = pour pousser le contenu de sa boite(ses modifs) vers GitHub

git push --set-upstream origin {prenom-nom} = Dit à Github qu'il doit créer ta branche également sur github.com et pas seulement en local

git checkout master "ou" nom de la branche = aller sur la branche nommée

git merge {prenom-nom} =   --> Applique tes changements de ta branche vers la branche "master"

[Explications pour lier un répo distant à un répo Github](https://gist.github.com/br1o/2761593)
