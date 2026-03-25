# FICHE 1 — Sécurisation des mots de passe

---

## Problématique

Comment sécuriser efficacement la modification d’un mot de passe dans une application ?

---

## Bonnes pratiques essentielles

### Complexité du mot de passe

Un mot de passe sécurisé doit :

* être long (au moins 12 caractères)
* contenir :

  * des majuscules
  * des minuscules
  * des chiffres
  * des caractères spéciaux

Objectif : rendre le mot de passe difficile à deviner ou à casser.

---

### Gestion du changement de mot de passe

Lors d’une modification, il faut toujours respecter l’ordre suivant :

1. Vérifier la complexité du mot de passe
2. Vérifier qu’il n’a jamais été utilisé auparavant
3. Enregistrer l’ancien mot de passe dans un historique
4. Mettre à jour le mot de passe actuel

Cet enchaînement correspond à une logique métier sécurisée attendue dans les épreuves du BTS .

---

### Sécurité globale

Un système de gestion des mots de passe doit :

* empêcher la réutilisation des anciens mots de passe
* conserver une trace des anciens mots de passe
* appliquer systématiquement des règles de validation

---

## Ce qu’il faut savoir pour le BTS

L’étudiant doit être capable de :

* identifier les règles de complexité dans un code
* comprendre le rôle des méthodes de validation
* compléter une méthode de modification de mot de passe
* respecter une logique métier cohérente et sécurisée

L’évaluation porte avant tout sur la compréhension et le raisonnement, plus que sur la syntaxe.

---

## Réflexe à retenir

VALIDER → CONTRÔLER → SAUVEGARDER → MODIFIER

---

## À retenir

Un mot de passe sécurisé repose à la fois sur sa complexité et sur la manière dont il est géré dans le temps.
