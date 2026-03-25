# FICHE 16 — Validation des données utilisateur

---

## Problématique

Pourquoi et comment valider les données saisies par un utilisateur ?

---

## Bonnes pratiques essentielles

### Principe

Toutes les entrées utilisateur doivent être considérées comme non fiables.

Objectif :

* éviter les erreurs
* empêcher les attaques

---

### Types de validation

* validation côté client (interface)
* validation côté serveur (obligatoire)

---

### Règles de validation

Les données doivent :

* respecter un format attendu
* être contrôlées (longueur, type, contenu)
* être nettoyées si nécessaire

---

### Exemples

* email valide
* mot de passe conforme
* champs obligatoires remplis

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* expliquer pourquoi valider les données
* identifier les risques liés aux entrées utilisateur
* proposer des contrôles adaptés

---

## Réflexe à retenir

TOUJOURS CONTRÔLER LES ENTRÉES

---

## À retenir

Une donnée utilisateur non validée peut devenir une faille de sécurité.
