Exercice n°1 :
Vous allez créer un projet sur votre dépot git.
Vous allez appeler votre projet “exercice1”
Ci-dessous les étapes à effectuer :
● En local, vous allez créer un projet qui sera composé d’un
fichier texte, qui s'appellera “fichier1” dans lequel vous saisir
le texte suivant :
○ Je suis l'exercice 1 de “votre prénom".
● Il faudra faire en sorte que ce fichier soit présent sur votre
dépôt distant sur git dans votre projet “exercice1”.
● une fois que cela aura été fait, il faudra créer un nouveau
fichier texte que l’on va appeler “fichier2”.
● Ce nouveau fichier devra contenir le texte suivant :
○ Je suis l'exercice 1 mais je suis le second fichier
● Ce fichier qui s’appelle fichier2 sera lui aussi pousser sur votre
dépôt distant au sein de votre projet “exercice1”.

git init
git add .
git commit -m "Commit 1 Exercice1"
git remote add origin https://github.com/VincentLip/Exercice1.git
git branch -M main
git push -u origin main
git add .
git commit -m "Commit 2 Exercice1"
git push -u origin main
