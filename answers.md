# Answers of Gabriel De Sousa Gabs2Sou 

## Basics
### Task 1
On retrouve:

un dossier .git : Permet à Git de stocker et d'organiser l'historique d'un projet.

un dossier img : Contient un schéma en format SVG représentant l’historique des commits, des branches, et des fusions dans le projet Git.

un fichier answers.md : Contient les réponses du laboratoire au format markdown.

### Task 2
Un Untracked Files du nom de README.md est apparu. Il est untracked car il est présent dans le répertoire de travail, mais qui n’est pas encore suivi par Git.

### Task 3
Le Untracked Files a maintenant disapru. Le README.md est maintenant dans un nouveau Staged Files.

### Task 4
Le fichier README.md est maintenant unstaged car on l'a modifié.

### Task 5
Chaîne de caractères : (a82f29b) -> Il s’agit d’un identifiant de commit abrégé

HEAD : C'est un pointeur spécial dans Git qui indique le commit courant. Ici, HEAD pointe sur le commit a82f29b, ce qui signifie que ce commit est le plus récent dans la branche active

main : C'est le nom de la branche principale du dépôt dans laquelle on travaille. Dans cet exemple, main est associée au commit a82f29b, indiquant que ce commit est le dernier sur la branche main.

Après les parenthèses : C'est le message du commit, en l'occurrence "ADD: README file".
### Task 6
Initial commit : Les fichiers et dossiers ont été réinitialisés à leur état de départ. Donc par exemple le fichier answers.md était à l'état de départ.

Dernier commit : Les fichiers et dossiers ont retrouvé leur état final. Donc par exemple le fichier answers contient de nouveau les réponses 1 à 5.

## Gitgraph
### Task 7
1) "develop" correspond au nom de la branche utilisée pour le développement en cours.

2) "baa6795" est le hash du commit, ces codes sont des identifiants unique pour chaque commit ce qui permet de les référer précisemment.

3) Il s'agit du message rentrer lors du commit.

4) Il s'agit de l'auteur du commit. C'est à dire l'auteur des modifications.

5) C'est la version du projet.

6) Il s'agit de la branche develop qui a été fusionné avec la branche main. 

7) Il s'agit de la branche feature-auth qui a été fusionné avec develop.

8) Il s'agit de la branche main. 

9) Ces commit font parties de la branche develop ou main et représentent l'historique des changements apportés. 

10) Il s'agit du commit initial du projet.
 

![Gitgraph](img/gitgraph.svg)