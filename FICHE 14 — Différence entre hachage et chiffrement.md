# FICHE 14 — Différence entre hachage et chiffrement

---

## Problématique

Quelle est la différence entre hacher et chiffrer une donnée, et dans quel cas utiliser chaque méthode ?

---

## Bonnes pratiques essentielles

### Hachage (hash)

Caractéristiques :

* transformation irréversible
* pas de clé
* impossible de retrouver la donnée initiale

Utilisation :

* stockage des mots de passe

---

### Chiffrement

Caractéristiques :

* transformation réversible
* nécessite une clé
* permet de retrouver la donnée

Utilisation :

* protéger des données sensibles (fichiers, communications)

---

### Comparaison

| Hachage               | Chiffrement           |
| --------------------- | --------------------- |
| irréversible          | réversible            |
| pas de clé            | clé nécessaire        |
| utilisé pour vérifier | utilisé pour protéger |

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* différencier les deux concepts
* choisir la bonne méthode selon le besoin
* justifier son choix

---

## Réflexe à retenir

MOT DE PASSE → HASH
DONNÉE À PROTÉGER → CHIFFRER

---

## À retenir

Le hachage sert à vérifier une information, le chiffrement sert à la protéger.
