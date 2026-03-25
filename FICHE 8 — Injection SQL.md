# FICHE 8 — Injection SQL

---

## Problématique

Comment empêcher qu’un utilisateur malveillant manipule une base de données via une faille dans les requêtes SQL ?

---

## Bonnes pratiques essentielles

### Principe de l’injection SQL

Une injection SQL consiste à :

* insérer du code SQL dans un champ de saisie
* modifier le comportement de la requête

Exemple :

* contourner une authentification
* modifier ou supprimer des données

Objectif de l’attaque : exploiter un manque de sécurisation des entrées utilisateur.

---

### Origine de la faille

La faille apparaît lorsque :

* les données saisies par l’utilisateur sont directement utilisées dans une requête SQL
* sans vérification ni protection

---

### Impacts possibles

Une injection SQL peut permettre :

* accès non autorisé aux données
* modification de données
* suppression de données
* contournement des règles métier

---

### Prévention

Pour sécuriser une application :

* utiliser des requêtes préparées (paramétrées)
* ne jamais concaténer directement les entrées utilisateur
* valider et filtrer les données saisies

Objectif : empêcher toute interprétation du contenu comme du code SQL.

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* expliquer le principe d’une injection SQL
* identifier une situation à risque
* comprendre les conséquences sur une application
* proposer des solutions de sécurisation

Ces notions sont évaluées dans les questions d’analyse de risques et de sécurité .

---

## Réflexe à retenir

NE JAMAIS FAIRE CONFIANCE AUX ENTRÉES UTILISATEUR

---

## À retenir

Une entrée utilisateur non contrôlée peut devenir une instruction SQL exécutée par la base de données.
