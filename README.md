git command --help

# first time
git config --global user.name "My Name"

git config --global user.email "user@email.com"

# new repo
git init

git remote add origin https://github.com/r1d/tmp.git

git pull              	: recupére les fichiers

git add .   	          : ajoute des fichiers

git add file1 file2   	: ajoute des fichiers

git status            	: état des modifs

git commit -a -m "text" : commit all en local (all & message)

git pull origin master	: récupére les modifs de master

git push origin master	: pousse la branche sur le master 

# branches
git branch            	: affiche la branche courante

git branche name      	: créé la branche name (vide)

git branch -d name    	: supprime une branche (-D sans vérif que les changements sont dans la branche courante)

git checkout name	      : change de branche

git merge name        	: merge la branche name avec la courante

git diff              	: différences et conflits du dernier commit

git diff master..name 	: différences entre 2 branches

# back to master & update

git checkout master

git pull

# remote
git init

git add .

git commit -m "inital commit"


git remote add github https://github.com/r1d/tmp.git

git push origin master


git remote add bitbucket https://edsi@bitbucket.org/edsi/tmp.git

git push github master

git push bitbucket master


git remote //liste

git remote -v

(git remote rename old new)

(git remote rm bitbucket)

# cheat sheet
GitHub git cheatsheet: help.github.com/git-cheat-sheets/
