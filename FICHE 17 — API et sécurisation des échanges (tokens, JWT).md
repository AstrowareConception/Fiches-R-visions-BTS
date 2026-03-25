# FICHE 17 — API et sécurisation des échanges (tokens, JWT)

---

## Problématique

Comment sécuriser les échanges entre un client (web/mobile) et une API ?

---

## Bonnes pratiques essentielles

### Principe des API

Une API permet à une application de :

* communiquer avec un serveur
* envoyer et recevoir des données

---

### Authentification par token

Après connexion :

* le serveur génère un token
* le client l’envoie à chaque requête

Objectif : éviter de renvoyer identifiant et mot de passe à chaque appel.

---

### JWT (JSON Web Token)

Un JWT contient :

* des informations sur l’utilisateur
* une signature garantissant son intégrité

Caractéristiques :

* autonome (pas besoin de session serveur)
* sécurisé si bien signé

---

### Sécurisation des échanges

Une API doit :

* vérifier le token à chaque requête
* refuser les requêtes non authentifiées
* utiliser HTTPS

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* comprendre le rôle d’une API
* expliquer le fonctionnement des tokens
* distinguer session et token
* proposer une sécurisation des échanges

---

## Réflexe à retenir

AUTHENTIFIER → TRANSMETTRE → VÉRIFIER

---

## À retenir

Un token remplace le mot de passe dans les échanges entre client et serveur.
