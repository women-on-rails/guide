---
layout: default
published: true
permalink: /get_project
---

# Récuperer un projet Women On Rails

## Avant de commencer

Nous  imaginons ici que votre projet s'appelle ````super_projet````. Pour récupérer votre projet, il faudra remplacer ````super_projet```` par le véritable nom de votre projet.  

## Dans la console

Ouvrez une console et entrez dans votre répertoire de travail (aidez vous des commandes ````cd```` (Changement de Dossier) et ````ls```` (LiSte des fichiers)).
Créez un nouveau dossier de travail (````mkdir```` : MaKe DIRectory):
``` Console
mkdir super_projet
````

Entrez dans ce dossier:
``` Console
cd super_projet
````

Initialisez GIT pour votre projet:
``` Console
git init
````

Vous allez maintenant lier votre répertoire ````super_projet```` situé sur votre ordinateur avec un répertoire distant super_projet situé sur votre compte github. Le lien sera appelé ````origin````.
Pour cela, créez un nouveau répertoire appelé ````super_projet```` sur Github et copiez l'url de ce répertoire.
Puis, faites la commande suivante, en remplaçant (votre compte) dans cette adresse par votre compte :

``` Console
git remote add origin git@github.com:(votre compte)/super_projet.git
````

Cela vous permet de synchroniser votre compte github avec les modifications que vous ferez sur le projet ````super_projet```` sur votre ordinateur.

À cette étape, si vous faites ````ls```` dans votre console, le dossier ````super_projet```` doit être vide.
Et si vous faites ````ls -a```` le dossier ````super_projet```` ne contient que les fichiers de configuration de git, dans le dossier caché ````.git````.

Maintenant, vous allez lier votre répertoire ````super_projet```` situé sur votre ordinateur avec le répertoire distant ````super_projet```` situé sur le compte des Women On Rails. Le lien sera appelé ````upstream````.
Pour cela, faites la commande suivante :

``` Console
git remote add upstream git@github.com:women-on-rails/super_projet.git
````

Cela va vous permettre de récupérer facilement le code existant nécessaire pour la suite de l'exercice. 

Pour récupérer ce code, faites la commande suivante :

``` Console
git pull upstream master
````

Cela remplit le dossier ````super_projet```` sur votre ordinateur avec tout ce que contient le projet ````super_projet```` sur le compte Github des Women On Rails.
En faisant un ````ls````, vous pourrez voir la liste des fichiers copiés. 

Vous voila prête pour l'exercice lié au projet Women On Rails !