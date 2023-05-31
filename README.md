# projet-blog-new
blog en php

git init 
git add . 
git commit -m "update"
 git remote add origin https://github.com/dgallula/projet-blog.git 
git branch -M master 
git push -u origin master 


git pull origin master
git commit -m "Merge remote changes"


Copy code
git branch new_branch
Passez à la nouvelle branche :

Copy code
git checkout new_branch
Effectuez un commit vide pour créer une référence commune entre les historiques :

php
Copy code
git commit --allow-empty -m "Merge branch histories"
Maintenant, vous pouvez essayer de fusionner la branche principale (master) avec votre nouvelle branche :

sql
Copy code
git merge master
Si vous avez des conflits lors de la fusion, résolvez-les manuellement en modifiant les fichiers concernés. Une fois les conflits résolus, enregistrez les modifications avec la commande git add et git commit.

Enfin, vous pouvez pousser vos modifications fusionnées sur le dépôt distant :

perl
Copy code


git add .
git commit -m "update"
git remote add origin https://github.com/dgallula/projet-blog.git
git branch -M main
git push -u origin main
