# Estimation PERT - 14/02/2023

- Méthode des points de fonction
    - Estimation par fonction utilisateur
    - Estimation par type de traitement: CRUD
    - Estimation par complexité des fonctions
    - Estimation par type de données: entrée, sortie, calulée

## Exercice 6

- Estimer le projet suivant, par la méthode des points de fonction:

## - Gérer les utilisateurs

|**Action**|**Réaliste**|**Optimiste**|**Pessimiste**|**Résultat**|
|:---|:---:|:---:|:---:|:---:|
|_Conception de 4 pages HTML et CSS_|1080 min (18h - 2,25 jrs)|900 min (15h - 1,87 jrs)|1500 min (25h - 3,12 jrs)|1299 min (21.66h - 2,70 jrs)|
|_Conception API avec NodeJS_|1080 min (18h - 2,25 jrs)|720 min (12h - 1,5 jrs)|1500 min (25h - 3,12 jrs)|1119,6 min (18.66h - 2,33 jrs)|

## - Affecter un rôle aux utilisateurs

|**Action**|**Réaliste**|**Optimiste**|**Pessimiste**|**Résultat**|
|:---|:---:|:---:|:---:|:---:|
|_Création d'une route PUT_|10 min|10 min|20 min|11,66 min|
|_Conception du contrôleur pour modifier un rôle_|50 min|30 min|60 min|180 min|
|_Implémentation de la feature_|10 min|20 min|50 min|68,33 min|

## - Consulter les rôles

|**Action**|**Réaliste**|**Optimiste**|**Pessimiste**|**Résultat**|
|:---|:---:|:---:|:---:|:---:|
|_Création d'une nouvelle route GET_|10 min|10 min|20 min|11,66 min|
|_Conception du contrôleur pour récupérer tous les rôles_|30 min|20 min|40 min|163,33 min|
|_Implémentation de la feature_|10 min|10 min|20 min|11,66 min|

## - Consulter l'ensemble des utilisateurs

|**Action**|**Réaliste**|**Optimiste**|**Pessimiste**|**Résultat**|
|:---|:---:|:---:|:---:|:---:|
|_Création d'une nouvelle route GET_|10 min|10 min| 20 min|11,66 min|
|_Conception du contrôleur pour récupérer tous les rôle et activités via des queries_|20 min|10 min|30 min|86,66 min|
|_Implémentation de la feature_|10 min|10 min|20 min|11,66 min|

## - Consulter l'ensemble des utilisateurs, leur rôle et leur activité sur le site
    
|**Action**|**Réaliste**|**Optimiste**|**Pessimiste**|**Résultat**|
|:---|:---:|:---:|:---:|:---:|
|_Création d'une nouvelle route GET_|10 min|10 min|20 min|11,66 min|
|_Conception du contrôleur pour récupérer tous les rôle et activités via des queries_|40 min|30 min|60 min|41,66 min|
|_Implémentation de la feature_|10 min|10 min|20 min|11,66 min|

## - Trier les utilisateurs par rôle et fréquence d'utilisation du site.

|**Action**|**Réaliste**|**Optimiste**|**Pessimiste**|**Résultat**|
|:---|:---:|:---:|:---:|:---:|
|_Création d'une nouvelle route GET_|10 min|10 min|20 min|11,66 min|
|_Conception du contrôleur pour récupérer tous les rôle et activités via des queries_|50 min|30 min|90 min| 53,33 min|                                                      
|_Implémentation de la feature_|10 min|10 min|20 min|11,66 min|
