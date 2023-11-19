# Reclamation Service

Le service Reclamation gère les réclamations dans une entreprise. Ce microservice utilise la base de données H2 et offre des fonctionnalités CRUD (Create, Read, Update, Delete) pour les réclamations.

## Fonctionnalités

- Afficher toutes les réclamations.
- Afficher une réclamation par son ID ou son type.
- Ajouter, modifier et supprimer une réclamation.

## Technologies Utilisées

- Java avec Spring Boot
- Base de données H2 (en mémoire)

## Prérequis

- Java JDK 8 ou supérieur
- Maven

## Configuration de la Base de Données

Le service utilise la base de données H2, qui est une base de données en mémoire. Aucune configuration supplémentaire n'est requise.

## Comment Exécuter le Service

1. Clonez le repository.

    ```bash
    git clone https://github.com/votre-utilisateur/reclamation-service.git
    ```

2. Naviguez vers le répertoire du projet.

    ```bash
    cd reclamation-service
    ```

3. Exécutez le service à l'aide de Maven.

    ```bash
    mvn spring-boot:run
    ```

Le service sera accessible à l'adresse [http://localhost:8085](http://localhost:8085).

## Endpoints de l'API
<!-- This is a comment in Markdown 
- **GET /reclamations :** Récupérer toutes les réclamations.
- **GET /reclamations/{id} :** Récupérer une réclamation par son ID.
- **GET /reclamations/type/{type} :** Récupérer une réclamation par son type.
- **POST /reclamations :** Ajouter une nouvelle réclamation.
- **PUT /reclamations/{id} :** Mettre à jour une réclamation par son ID.
- **DELETE /reclamations/{id} :** Supprimer une réclamation par son ID.
-->
## Exemples d'Utilisation

### Récupérer toutes les réclamations

```bash
curl http://localhost:8085/reclamations
