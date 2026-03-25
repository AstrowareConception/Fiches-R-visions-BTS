# FICHE 15 — Authentification sécurisée

---

## Problématique

Comment renforcer la sécurité de l’authentification des utilisateurs ?

---

## Bonnes pratiques essentielles

### Authentification classique

Basée sur :

* identifiant
* mot de passe

Limite : vulnérable si le mot de passe est compromis.

---

### Authentification forte (MFA)

Ajout d’un second facteur :

* code SMS
* application mobile
* clé physique

Objectif : renforcer la sécurité.

---

### Gestion des tentatives

Le système doit :

* limiter le nombre de tentatives
* bloquer temporairement un compte
* enregistrer les tentatives

---

### Gestion des sessions

Une session doit :

* expirer après un certain temps
* être invalide après déconnexion
* être sécurisée (cookies protégés)

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* proposer des améliorations d’authentification
* comprendre les risques liés aux mots de passe
* expliquer l’intérêt du MFA

---

## Réflexe à retenir

IDENTIFIER → VÉRIFIER → RENFORCER

---

## À retenir

Un mot de passe seul ne suffit pas à sécuriser un accès.
