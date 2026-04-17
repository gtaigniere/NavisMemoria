# Projet NavisMemoria

### Backend

Généré avec spring initializr :

Maven, Spring 3.5.13, Java 17.0.14, et les dépendances :
Spring Web, MySQL Driver, Spring Data JPA, Lombok, Spring Boot DevTools, et Spring Security.

### Frontend

Généré avec Angular CLI 21.2

## Description

Plateforme qui recense les différents, sous-marins et navires de guerre, principalement allemands et de la seconde guerre mondiale, et met à disposition des articles qui en présente les plus emblématiques.

### Auteur

Gilles T.

## Commandes Angular

Création de différents éléments :

- *`ng generate component <chemin/nom-composant>`*
- *`ng generate directive <chemin/nom-directive>`*
- *`ng generate pipe <chemin/nom-pipe>`*
- *`ng generate service <chemin/nom-service>`*
- *`ng generate class <chemin/nom-classe>`*
- *`ng generate interface <chemin/nom-interface>`*
- *`ng generate enum <chemin/nom-enum>`*
- *`ng generate module <chemin/nom-module>` ou avec routage : `ng g m <chemin/nom-module> —routing`*
- *`ng generate guard <chemin/nom-guard>`*
- *`ng generate interceptor <chemin/nom-interceptor>`*
- *`ng generate resolver <chemin/nom-resolver>`*

## Gestion du développement

### Création d’une branche

- Mise à jour du dépôt local : `git fetch origin`
- Création de la branche de développement : `git checkout -b NMEMORIA-XXX origin/develop` (où NMEMORIA-XXX est la référence de la "JIRA" associée)

### Commit sur la branche

- Sélection des changements à commit
- Ecriture du message du commit :

```
NMEMORIA-XXX : titre du commit explicite
* liste de détails éventuels
```

Il faut envoyer les commits sur le dépôt régulièrement : `git push origin NMEMORIA-XXX`

- Si le commit précédemment envoyé a été modifié, il faut forcer le push : `git push -f origin NMEMORIA-XXX`
