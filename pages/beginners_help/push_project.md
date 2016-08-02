---
layout: default
published: true
permalink: /push_project
---

# Enregistrer ses modifications sur le dépôt distant

## Avant de commencer

Nous  imaginons ici que votre projet s'appelle ````super_projet````. Pour récupérer votre projet, il faudra remplacer ````super_projet```` par le véritable nom de votre projet.  

## Committer et Pusher

Lorsque vous avez fait des modifications dans votre projet ````super_projet````, vous pouvez avoir besoin de les enregistrer pour ne pas les effacer malencontreusement. Pour cela, vous allez les ````commit```` (par abus de langage en français "commiter") : sauvegarder l'ensemble des modifications, pas pour votre éditeur de texte, mais pour git.

Pour voir les différences entre ce que vous avez en ce moment dans les fichiers et ce que git a compris "depuis la dernière sauvegarde", vous pouvez lancer la commande suivante :

``` Console
git status
````

Vous verrez ce qui n'est pas encore "dans git", en rouge.

Pour committer ces changements, vous devez d'abord les ajouter aux modifications à prendre en compte avec la commande :

``` Console
git add .
````

Si vous souhaitez ne prendre en compte que certaines modifications et pas d'autres, vous pouvez utiliser la commande :

``` Console
git add -p 
````

Cela vous permettra de visualier chaque modification et de l'ajouter (````y````) ou non (````n````). 

Quand vous aurez ajouté ce que vous voulez, vous pouvez à nouveau lancer la commande :

``` Console
git status
````
Vous verrez ce qui n'est pas dans votre commit en rouge, et ce qui sera ajouté dans le prochain commit en vert.

Pour "vraiment" enregistrer les modifications "en vert", il faut faire la commande :

``` Console
git commit 
````

Il est vraiment pratique de décrire le contenu de votre commit, pour vous ou pour les autres.
Vous pouvez y ajouter un message avec l'option ````-m```` suivie du message :

``` Console
git commit -m "ce commit sert à faire ceci"
````
Cela permet de savoir rapidement à quoi correspond le commit, au lieu de regarder sa composition. 

Pour envoyer votre commit vers votre repertoire distant (sur Github), vous devez ensuite utiliser la commande ````push````:

```Console
git push 
````