# cours-A61
Préparation de la solution d'IA pour la mise en production

Étapes complétés:

1.init setup-cours-A61
2.Pipeline-complet-cours-A61
3.prediction et test


____________________________________________________________________________________
Defits du projets:

Création de la branche principal.
Une branche par étape est créé et fusioné ensuite avec la branche principale.
Permet d’avoir un ‘main’ propre. Il est plus facile de supprimer une branche lors d’erreur et de recommencer l’étape qui cause le trouble que de reprendre le ‘main’ et/ou de le corriger …
Garder un main propre est très important. Les branches permettent de travailler sur plusieurs étapes/features comme celle du TP …
Donc les étapes ont été les suivantes, 
1)	Créé le main 
2)	Crée la branche de travailles, et pointer le répertoire vers la nouvelle branche
3)	Ajouter/modifier les fichiers, exécuter les .py et les tox, etc… 
4)	Après succès de l’étape commiter et pousser dans la branche
5)	Un fois pousser un fusionne la branche avec le main (Pull request)
6)	On recommence avec la prochaine étape du TP et retour au #2 du processus

Quelque défit :
Étape1:
1 – Ajustement du Tox pour utiliser l’ENV de Conda avec tox-conda dans tox.ini
-	Sinon les Packages n’était pas inclut dans le bon environnement.
-	Et pour utiliser les packages d’un environnement Anaconda on utilise tox-conda
Étape 2
Ajout des fichiers __init__.py qui sont manquant dans les répertoires de packages
