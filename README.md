# JustDab

JustDab est une application disponible à travers les distributeurs automatiques de billet qui permet à ses clients de disposer d’un compte bancaire unique depuis lequel ils peuvent effectuer des actions courantes de gestion d’argent liquide et bénéficier du service d’un conseiller particulier pour répondre à leur problèmatique.

## Fonctionnalités attendues
1. En tant que client, je veux pouvoir consulter mon compte bancaire afin de vérifier mon solde disponible.
2. En tant que client, je veux pouvoir déposer de l’argent liquide afin d’augmenter mon solde disponible.
3. En tant que client, je veux pouvoir retirer de l’argent liquide afin d’effectuer des achats.
4. En tant que client, je veux avoir connaître le conseiller qui m’est attribué afin de pouvoir le contacter.
5. En tant que conseiller, je veux pouvoir consulter la liste de mes clients afin de pouvoir les contacter.
6. En tant que conseiller, je veux pouvoir consulter la liste de l’ensemble des clients possédant un compte afin de pouvoir leur envoyer une offre promotionnelle.

## Contraintes technologiques
- Java 21
- Spring Boot 3
- MySQL 5

## Contraintes de conception
- Client et employé héritent tous les deux d’une même classe utilisateur.
- Chaque fonctionnalité doit pouvoir être atteinte par le biais d’une requête HTTP respectant la norme REST.
- Il n’est pas nécessaire d’implémenter un système d’authentification.
- Des données simulées doivent être générées en base de donnée au lancement de l’application par le biais d’un fichier data.sql (lancé automatiquement par JPA)

## Conseils
- Créer le projet via spring Initializr
- Penser à vos modèles d’objet avant le début du projet a l’aide de diagramme UML
