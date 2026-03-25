# FICHE 20 — Gestion des erreurs et exceptions

---

## Problématique

Comment gérer les erreurs dans une application sans provoquer de dysfonctionnement ou de faille ?

---

## Bonnes pratiques essentielles

### Principe

Une erreur doit :

* être détectée
* être gérée
* ne pas bloquer l’application

---

### Gestion des exceptions

En Java :

```java
try {
    // code
} catch (Exception e) {
    // gestion
}
```

Objectif :

* éviter un arrêt brutal
* contrôler le comportement

---

### Bonnes pratiques

* ne jamais afficher des erreurs techniques à l’utilisateur
* enregistrer les erreurs dans des logs
* prévoir des messages clairs

---

### Sécurité

Une mauvaise gestion des erreurs peut :

* révéler des informations sensibles
* faciliter des attaques

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* comprendre le mécanisme des exceptions
* proposer une gestion adaptée
* expliquer les enjeux de sécurité

---

## Réflexe à retenir

DÉTECTER → GÉRER → INFORMER

---

## À retenir

Une erreur bien gérée améliore la stabilité et la sécurité de l’application.
