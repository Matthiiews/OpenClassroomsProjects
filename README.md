![chess_club](img/chess_club.png)

# Projet 4 Développeur d'application-Python OpenClassrooms 
***Livrable du Projet 4 du parcours Dévelpppeur d'application Python d'OpenClassrooms : application de gestion de tournoi d'échecs avec base de données.***

_Testé sous Windows 10 - Python version 3.11.4

## Table des matières
1. [Initialisation du projet](#id-section1)
    1. [Windows](#id-section1-1)
    1. [MacOS et Linux](#id-section1-2)
    3. [Générer un rapport flake8](#id-section1-3)
2. [Options des menus](#id-section2)
    1. [Menu principal](#section2-1)
    2. [Rapports](#section2-2)


<div id='id-section1'></div>

## 1. Initialisation du projet

<div id='id-section1-1'></div>

#### 1.1 Windows :
Dans Windows Powershell ou Gitlab, naviguer vers le dossier souhaité.
###### Récupération du projet

    $ git clone https://github.com/Matthiiews/OpenClassroomsProjects.git

###### Activer l'environnement virtuel
    $ cd Project_Chess
    $ python -m venv env 
    $ ~env\scripts\activate
    
###### Installer les paquets requis
    $ pip install -r requirements.txt

###### Lancer le programme
    $ python main.py

<div id='id-section1-2'></div>

---------

#### 1.2 MacOS et Linux :
Dans le terminal, naviguer vers le dossier souhaité.
###### Récupération du projet

    $ git clone https://github.com/Matthiiews/OpenClassroomsProjects.git

###### Activer l'environnement virtuel
    $ cd cd Project_Chess 
    $ python -m venv env 
    $ source env/bin/activate
    
###### Installer les paquets requis
    $ pip install -r requirements.txt

###### Lancer le programme
    $ python main.py

<div id='id-section1-3'></div>

----------

#### 1.3 Générer un rapport flake8

    $ flake8 --format=html --htmldir=flake8_report

**Vous trouverez le rapport dans le dossier _'flake8-report'_.**

_Dernier rapport exporté :_

![latest_report](img/latest_report.png)

<div id='id-section2'></div>

## 2. Options des menus

<div id='id-section2-1'></div>

#### 2.1 Menu Principal
![main_menu](img/main_menu.png)
1. Créer un nouveau tournoi
2. Reprendre tournoi existant
3. Créer un nouveau joueur
4. Modifier un joueur existant
5. Rapports

<div id='id-section2-2'></div>

#### 2.2 Rapports
1. Tous les joueurs
   1. Classer par nom
   2. Classer par rang
2. Tous les joueurs d'un tournoi
   1. Classer par nom
   2. Classer par rang
3. Tous les tournois
4. Toutes les rondes d'un tournoi
5. Tous les matchs d'un tournoi
#### 2.3 Menu des rapports
![main_menu](img/reports_menu.png)

<div id='id-section3'></div>

## 3. Exemples d'affichage
#### Matchs d'une ronde :
![round](img/round_example.png)

#### Rapport des joueurs :
![player_report](img/players_report.png)

#### Rapport des rondes :
![round_report](img/rounds_report.png)