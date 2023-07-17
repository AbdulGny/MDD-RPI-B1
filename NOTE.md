# Note Modélisation de données.

# INTRODUCTION 
- Créer un dépot, se positionner sur un répertoire et executer; (cd)
- git init pour initialiser le projet sur le répertoire séléctionner qui devient un dépot git
qui sauvegarde les modifications éffectué au sein du dossier

- git status (pour verifié si tout a été sauvegarder)
- Pour sauvegarder en premier temps git status, et pour ajouter des fichiers au suivi  ' git add . '
- apres ajout laissez un message commit en mettant git commit -m "message ";
- Merise ( methode d'etude et de realisation informatique pour les systèmes d'entreprise)
    3 point clés 
    - une approche systemique: on transforme les processus de l'entreprise en SI
    - une séparation de données et de traitements 
    - une approche nivelée 

- La séparation des données et des traitements
la séparation des données et des traitements permet de séparer les donées du systeme d'information et les traitement effectués sur ces données
Cette demarche se fait en 3 etapes
-l'analyse des plux : on analyse les flux d'informations entre les acteurs du systeme d'information et les acteur du systeme operant 
-l'etude des documents interne (facture, bon de livraison)
-l'etude des documents en externes (fournisseur,clients)ce sont les documents qui sont ecahnges entre le si et le systeme operant

Les differentes types d'information 

- Les infos de bases ou elementaire ce sont les données de base du SI 
- les informations calculées ce sont les données calculées a partir des données de bases
- les traitement ou les fonctions ce sont les traitement effectues sur les données de base pour obtenir les données calculées

En résumé vous devrez identifier les données et les traitement effectues sur ces données

LAPPROCHE NIVELEE

Pour effectuer la conception d'un SI, on va utiliser une appriche nivélée. Cette approche se compose de niveau 
- niveau conceptuel 
- niveau organisationnel
- niveau logique
- niveau physique

Niveau conceptuel 

le niveau conceptuel permet de modeliser les donnees de l'entreprise on va utiliser le modele conceptuel de données mcd pour modeliser les donnes de l'entreprise , et le mct pour modeliser les traitement effectue sur ces données.


Niveau ORGANISATIONNEL 

Le niveau organisationnel va permettre d'intefrer a l'analyse precedente toutes les notions de temporalite de chronologie des operations de contraintes geographique on va utiliser le modele organisationnel des traitement et le modele organisationnel des donnes mod mot pour modeliser les traitement de l'entreprise.

En resume on se pose les questions suivante a partir des donnes recueillies au niveau conceptuel
- quand les traitements sont ils effectuée 
- ou les traitements sont ils effectué 
- par qui les traitements sont ils éffectués

niveau LOGIQUE 

le niveau logique va permettre de modeliser les donnes de l'entreprise en utilisant le modele logique de donnes mld et les traitements de lentreprise en utilisant le modele liguqe des traitement 

le mld est independant des language de programmation et des sgbd 

On repond a la question avec quoi les traitement sont ils effectués

Le niveau PHYSIQUE 

Ils s'agit de lorganisation reelle des donnes on va utiliser le modele physique de donnes mdp et le modele physique des traitements

Ici on apporte des solutions technique de stockage des donnes et de traitements des données 

On repond a la question comment les traitements sont ils effectués ?


RESUME LES 4 NIVEAU DE MERISE 

