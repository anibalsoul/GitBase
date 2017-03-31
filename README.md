# Les bases de GIT

On apprend les bases de Git


## Premier article
1. A  
2. B
3. C
=======
## Quelques commandes de base

1. git init // Initialiser le dépôt GIT dans un projet (c:\xampp\htdocs\git\01-commandes)
2. git remote add origin https://github.com/rorschach59/GitBase.git // Pour se connecter à notre base GitHub (travailler sur c:\xampp\htdocs\git\01-commandes)
3. git add .  // Ajoute un fichier dans la liste d'attente (c:\xampp\htdocs\git\01-commandes)
4. git status // Montre les fichiers en attente (c:\xampp\htdocs\git\01-commandes)
5. git commit -m "J'ai crée de nouveaux fichiers" // Inscrit une nouvelle modification avec un commentaire (c:\xampp\htdocs\git\01-commandes), commente les fichiers ajoutés avec git add .
6. git log  // Affiche tous les commit (c:\xampp\htdocs\git\01-commandes)
7. git push -u origin master  // Ajoute les fichiers sur GitHub (c:\xampp\htdocs\git\01-commandes)
8. git clone https://github.com/rorschach59/GitBase.git 02-commandes-pull // Récupère les fichiers depuis GitHub (travailler sur c:\xampp\htdocs\git)

- git branch contact  // Créer une branche qui s'appelle contact
- git branch -d contact // Supprime la branche contact
- git push origin delete --contact // Supprime la branche contact
- git branch -a // Affiche les branches
- get checkout contact  // Switch sur la branche contact

npm install -g ungit // pour voir les branches plus facilement
ungit // pour initialiser
taper l'url du projet
