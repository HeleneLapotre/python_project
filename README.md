# Python Project

## Description des donées
Description des données :

Ici, les données recueillies proviennent d'une expérience dans laquelle on présentait à des participants différents objets sur une table tactile, on a donc récupéré différents temps de réaction. Le sujet portait des lunettes qui lui obstruait la vue, qui s'ouvrait lorsque l'objet était placé. Il tenait appuyé un bouton d'une manette, qu'il devait relâcher quand ses lunettes s'ouvraient et aller récupérer l'objet. Les temps de réaction récoltés correspondent donc à l'intervalle de temps entre le moment où ses lunettes s'ouvrent et le moment où il relâche son bouton et l'intervalle entre le bouton relâché et le moment où il attrape l'objet.

Les objets présentés avaient différents types d'ombre :
- sans ombre ( = 0)
- avec l'ombre normal de l'objet ( = 1)
- avec l'ombre normal de l'objet mais inversé ( = 2)
- avec l'ombre d'un autre objet ( = 3)
Ce fichier est un markdown. Si besoin d'une mise en page particulière (gras, italique...), se référer à la doc sur markdown.


## Installation de Git/Github
1. Via le terminal (iTerm) dans un dossier où il veut récupérer le repo (ex: Documents), taper git clone https://github.com/USER/python_project.git

Pour Pusher 
1. S’assurer que tu es situé en local dans ton dossier python project (exemple : MacBook-Pro-de-Helene:python_project helene$) 
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
