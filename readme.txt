commandes Git Bash :

cd .. : remonte d'un cran

cd nomdudossier : se déplacer dans un autre dossier

mkdir nomdudossier : crée un dossier

touch nomdufichier.txt : crée un fichier

git config --global user.name 'nom prenom' : configurer le nom de l'utilisateur

git config --get user.name : ressort le nom du compte utilisateur

git config --global user.email 'email@domaine.com' : configurer l'email de l'utilisateur

git config --get user.email : ressort l'email de l'utilisateur

git init : initialise le projet

ls : affiche les fichiers/dossiers présents dans le dossier

ls -a : affiche les fichiers/dossiers cachés

git status : affiche le statut git (fichiers suivis etc)

git add nomdufichier.txt : ajoute le fichier à git

git add . : ajoute tous les fichiers non trackés

git rm --cached numdufichier.txt : enlève le fichier

git commit -m 'message' : publie le fichier et affiche le message

ssh-keygen -t ed25519 -C "Jeremie.Mace@etu.univ-grenoble-alpes.fr" : crée un espace et génère une clé ssh (dans le fichier en .pub)



Logiciels de fusion pour les changements de version :

git config --global core.editor vim

git config --global merge.tools vimdiff