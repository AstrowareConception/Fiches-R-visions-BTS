# FICHE 12 — Sécurisation globale d’une application

---

## Problématique

Comment sécuriser une application informatique dans son ensemble pour limiter les risques et protéger les données ?

---

## Bonnes pratiques essentielles

### Authentification

Permet de vérifier l’identité de l’utilisateur :

* identifiant et mot de passe
* gestion de session

Objectif : s’assurer que l’utilisateur est bien connu du système.

---

### Habilitation

Permet de contrôler les actions autorisées :

* accès limité selon le rôle
* restrictions sur les fonctionnalités

Objectif : empêcher les accès non autorisés.

---

### Validation des données

Toutes les entrées utilisateur doivent être :

* contrôlées
* validées
* filtrées

Objectif : éviter les attaques (injection SQL, erreurs).

---

### Protection des actions sensibles

Certaines actions doivent être sécurisées :

* modification de mot de passe
* suppression de données

Exemple :

* utilisation de tokens (CSRF)

Objectif : éviter les actions frauduleuses.

---

### Journalisation (logs)

Le système doit :

* enregistrer les événements importants
* permettre une analyse des incidents

Objectif : détecter les comportements anormaux.

---

### Protection des données

Les données doivent :

* être sécurisées
* respecter le RGPD
* être accessibles uniquement aux personnes autorisées

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* identifier les différents mécanismes de sécurité
* comprendre leur rôle dans une application
* proposer des améliorations de sécurité
* analyser une application existante

Ces compétences sont évaluées de manière transversale dans les études de cas .

---

## Réflexe à retenir

AUTHENTIFIER → CONTRÔLER → VALIDER → SURVEILLER

---

## À retenir

La sécurité d’une application repose sur un ensemble de mécanismes complémentaires, pas sur une seule protection.
