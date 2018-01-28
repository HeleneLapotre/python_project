# Python Project

Installation de Git/Github

1. Via le terminal (iTerm) dans un dossier où il veut récupérer le repo (ex: Documents), taper git clone https://github.com/HeleneLapotre/python_project.git

Pour Pusher 

1. S’assurer que tu es située en local dans ton dossier python project (MacBook-Pro-de-Helene:python_project helene$) 
2. Git Status = pour voir les fichiers que tu as modifié en local et qui ne sont pas présents sur Github
3. Git add . = pour prendre tous les fichiers « en rouge » ou git add nom_du_fichier pour prendre qu’un seul fichier 
4. Git commit -m « update Readme »
5. Git push origin master

Pour manipuler une branche

1. Se mettre dans la branche master en local (git checkout master)
2. S’assurer d’avoir la dernière version de master (git pull origin master)
3. Créer la nouvelle branche (git checkout -b "feature/test ») 
4. Une fois la feature terminée et validée, pour supprimer la branche aller sur master et faire git branch -D feature/test 

Commandes Terminal 

cd : pour revenir à la racine peu importe où tu te trouves (cd) 
ls : voir ce qui se trouve depuis où tu es 
cd : pour rentrer dans un dossier (cd nom_dossier)
mkdir : pour créer un dossier (mkdir nom_dossier)
touch : pour créer un fichier (touch nom_fichier)
rm -rf : pour supprimer un fichier 
open : pour ouvrir un fichier
