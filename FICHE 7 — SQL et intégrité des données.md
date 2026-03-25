# FICHE 7 — SQL et intégrité des données

---

## Problématique

Comment garantir la cohérence et la sécurité des données dans une base de données ?

---

## Bonnes pratiques essentielles

### Modification de structure (ALTER TABLE)

Permet d’adapter une table existante :

Exemples :

* ajouter un champ
* modifier un attribut
* ajouter une contrainte

Objectif : faire évoluer la base de données sans la recréer.

---

### Requêtes de contrôle (SELECT)

Permettent de vérifier la cohérence des données :

Exemples :

* détecter des valeurs incohérentes
* identifier des anomalies

Objectif : repérer des erreurs ou des fraudes.

---

### Intégrité des données

Les données doivent respecter des règles métier :

Exemples :

* un montant doit être positif
* un acompte ne peut pas dépasser un total
* une valeur minimale doit être respectée

Objectif : garantir la fiabilité des données.

---

### Déclencheurs (triggers)

Un trigger est exécuté automatiquement lors d’une action (INSERT, UPDATE).

Utilisation :

* vérifier des règles métier
* bloquer une insertion incorrecte

Exemple :

* refuser un contrat si le montant est incohérent

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* écrire une requête ALTER TABLE
* écrire une requête SELECT avec conditions
* comprendre et compléter un trigger
* appliquer des règles métier dans une base de données

Ces compétences sont directement évaluées dans les exercices SQL .

---

## Réflexe à retenir

VÉRIFIER → CONTRÔLER → BLOQUER

---

## À retenir

Une base de données fiable repose sur des règles métier appliquées directement au niveau des données.
