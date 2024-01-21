# cours-A61
Préparation de la solution d'IA pour la mise en production

Étapes complétés:

1. init setup-cours-A61
2. Pipeline-complet-cours-A61
3. prediction et test
4. ajout validation de données
5. ajout ingenierie de fonctionnalités
6. gestion des versions& journalisation
7. package building
8. creation the api skeleton
9. Setup Config and Logging- tests flask-app
10. Ajout-prédiction-test à notre Flask api
11. Ajout de version a notre api
12. Ajout-Schema de validation-API flask
13. Configurer Circle CI
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

Étape 8
Le path dans le requirements.txt a du être changé et la version de Flask aussi de  1.0.2 à 3.0.1

Étape 9
Grosse problématique de python vs Conda, le chemin après la création du répertoire .tox  semble être le path d'un autre poste. Très Très bizarre. Voir le fichier word pour de plus ample explication.
