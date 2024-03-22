# Documentation du projet footpro

Ce projet utilise Docker pour fournir un environnement de développement local comprenant MySQL, phpMyAdmin et le site web Footpro

## Mise en place de l'environnement Docker

1. **Installation de Docker :** Assurez-vous d'avoir Docker installé sur votre système. Vous pouvez le télécharger à partir du [site officiel de Docker](https://www.docker.com/get-started).

2. **Configuration de Docker Compose :** Utilisez le fichier `docker-compose.yml` fourni pour démarrer les services Docker nécessaires.

    ```bash
    docker-compose up -d
    ```

## Accès aux services Docker

- **phpMyAdmin :** Accédez à phpMyAdmin via [http://localhost:9995](http://localhost:9995) dans votre navigateur. Utilisez les informations d'identification MySQL configurées dans le fichier `docker-compose.yml` pour vous connecter.