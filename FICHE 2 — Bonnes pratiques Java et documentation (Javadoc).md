# FICHE 2 — Bonnes pratiques Java et documentation (Javadoc)

---

## Problématique

Comment écrire un code Java lisible, maintenable et compréhensible par d’autres développeurs ?

---

## Bonnes pratiques essentielles

### Nommage des éléments

En Java, le nommage doit respecter des conventions strictes :

* Classes :

  * première lettre en majuscule
  * style CamelCase
  * noms explicites
  * exemple : `Utilisateur`, `ClientPremium`

* Méthodes :

  * première lettre en minuscule
  * verbe décrivant une action
  * exemple : `modifierMdp()`, `verifierMdp()`

* Variables :

  * première lettre en minuscule
  * nom descriptif
  * exemple : `motDePasse`, `nbTentatives`

Objectif : rendre le code compréhensible immédiatement.

---

### Lisibilité et structure

Un code de qualité doit :

* être clair et compréhensible sans explication orale
* utiliser des noms explicites plutôt que des abréviations
* éviter les structures complexes inutiles
* être correctement indenté

Objectif : faciliter la maintenance et la relecture.

---

### Documentation Javadoc

Chaque méthode importante doit être documentée avec Javadoc.

Structure attendue :

```java
/**
 * Description du rôle de la méthode
 * @param nomParam description du paramètre
 * @return description de la valeur retournée
 */
```

Exemple :

```java
/**
 * Modifie le mot de passe de l'utilisateur
 * @param valMdp nouveau mot de passe
 * @return true si la modification a réussi, false sinon
 */
```

Objectif : permettre à un autre développeur de comprendre rapidement le fonctionnement.

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* identifier des erreurs de nommage
* corriger un code pour respecter les conventions Java
* rédiger une documentation Javadoc correcte
* expliquer l’intérêt des bonnes pratiques

Ces éléments sont explicitement attendus dans les questions d’analyse de code .

---

## Réflexe à retenir

NOMMER → STRUCTURER → DOCUMENTER

---

## À retenir

Un bon code n’est pas seulement fonctionnel : il doit être lisible, compréhensible et maintenable.
