Petit glossaire :

git add :Ajouter le fichier modifié à la liste des fichiers qui seront envoyés au serveur
Commit (valider) : valider des modifications avant de les envoyer au serveur
Push (pousser) : lorsque vous envoyez des fichiers sur le serveur, vous faites un “push”
Repository (“dépôt” en français) : il s’agit de l’espace de stockage que vous allez créer sur le serveur pour y déposer les fichiers de votre projet
Clone (cloner) : lorsque vous copiez pour la première fois un projet sur votre ordinateur à partir du serveur. Les mises à jours des fichiers par la suite seront des “pull”
Master/main (maître) : il s’agit de la branche principale du projet
git init : Initialiser Git dans le dossier de votre projet sur votre ordinateur
git pull origin master : Récupérer la dernière version des fichiers du projet sur le serveur
git status : Consulter les fichiers que l’on a ajoutés à l’index avec “git add”
git log : Obtenir la liste des commits qui ont été faits précédement 
git config - - global user.name « mon nom » : Définir son nom
git config - - global user.email « mon email » : Définir mon adresse mail
git - - version : Vérifier sa version de GIT
cd nomdudossier : Naviguer dans un dossier
git diff : Afficher les modifications apportés aux fichiers
ls : Lister les éléments dans un dossier
git switch - : pour revenir où on était (revenir au master)
git push --tags : pousser tous les tags
git push origin <nom du tag> : pousser un tag
pwd : le chemin de mon repo
git clone : cloner un repertoire
un conflit : Les conflits surviennent généralement lorsque deux personnes ont modifié les mêmes lignes dans un fichier, ou si un développeur a supprimé un fichier alors qu'un autre développeur le modifiait. ... Git marquera le fichier comme étant en conflit et arrêtera le processus de merge
git restore staged <nom du fichier à modifier> : supprimer le add tout juste ajouté
git log --oneline --decorate --graph : pour voir les branches en graph