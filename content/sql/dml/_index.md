---
title: "DML"
date: 2023-08-26T13:15:51+02:00
draft: false
---

Langage de manipulation des données (DML) - Le langage de manipulation des données est le sous-langage qui permet d'ajouter, de modifier ou de supprimer des données dans une base de données. En SQL, il correspond aux langages INSERT, UPDATE et DML. DELETE

## Insérer des données

L’insertion de données dans une table s’effectue à l’aide de la commande INSERT INTO. Cette commande permet au choix d’inclure une seule ligne à la base existante ou plusieurs lignes d’un coup.

Insertion d’une ligne à la fois
Pour insérer des données dans une base, il y a 2 syntaxes principales :

- Insérer une ligne en indiquant les informations pour chaque colonne existante (en respectant l’ordre)
- Insérer une ligne en spécifiant les colonnes que vous souhaiter compléter. Il est possible d’insérer une ligne renseignant seulement une partie des colonnes

## Supprimer des données

La commande DELETE en SQL permet de supprimer des lignes dans une table. En utilisant cette commande associé à WHERE il est possible de sélectionner les lignes concernées qui seront supprimées.

Attention
Avant d’essayer de supprimer des lignes, il est recommandé d’effectuer une sauvegarde de la base de données, ou tout du moins de la table concernée par la suppression. Ainsi, s’il y a une mauvaise manipulation il est toujours possible de restaurer les données.
