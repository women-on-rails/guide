---
layout: default
published: true
permalink: /git_commands
---

# Commandes principales de Git

Git est un outil permettant de travailler en équipe et de versionner son travail.

Voici les commandes principales que nous allons utiliser tout au long du projet, pour utiliser Git:

- git init : Utile pour tout nouveau projet. Cela permet d'initialiser git dans le dossier de travail.
- git clone : Crée une copie du projet distant (ce que vous voyez sur github par exemple) sur votre orginateur (en local).
- git status : Permet de voir les différences entre ce que vous avez en ce moment dans les fichiers et ce que git a compris "depuis la dernière sauvegarde". Exemple: ``` git status ```
- git add : Ajoute un changement aux modifications à prendre en compte (à l'index). Exemples: ``` git add -p ``` pour choisir l'ajout fichier par fichier, ```git add . ``` pour tout ajouter
- ```git commit -m "Mon message"``` : Permet d'enregistrer de manière permanente en y associant un message.
- ```git push origin master``` : Envoie toutes les modifications enregistrées vers le répertoire distant (vers Github dans notre cas)

# Pour aller plus loin

- Commencer avec GIT [ici](http://christopheducamp.com/2013/12/15/github-pour-nuls-partie-1/) ou [ici](http://rogerdudler.github.io/git-guide/index.fr.html)
- Aller plus loin avec les [répertoires distants](https://git-scm.com/book/fr/v1/Les-bases-de-Git-Travailler-avec-des-d%C3%A9p%C3%B4ts-distants)
- Premiers pas en [CSS](http://css.mammouthland.net/premiers-pas-en-css.php)
- Principales balises en [HTML](https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/memento-des-balises-html ou http://www.vieytes.org/tbalises.html)
- Guide complet sur le [HTML](http://www.lehtml.com/html/index.htm)
- Les clés [SSH](http://sebsauvage.net/comprendre/ssl/)