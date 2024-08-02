# Library Project

## Description

Library Project est une application de gestion de bibliothèque développée avec Laravel. Elle permet de gérer les livres, les membres et les emprunts de manière efficace.

## Fonctionnalités

- Ajouter, modifier et supprimer des livres.
- Ajouter, modifier et supprimer des membres.
- Gérer les emprunts et les retours de livres.
- Rechercher des livres et des membres.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [PHP](https://www.php.net/manual/en/install.php) (version 7.4 ou supérieure)
- [Composer](https://getcomposer.org/download/)
- [Laravel](https://laravel.com/docs/5.2)

## Installation

1. Clonez ce dépôt sur votre machine locale :

    ```bash
    git clone https://github.com/Orelson14/library_project.git
    ```

2. Accédez au répertoire du projet :

    ```bash
    cd library_project
    ```

3. Installez les dépendances du projet :

    ```bash
    composer install
    ```

4. Copiez le fichier d'exemple `.env` et configurez les paramètres nécessaires :

    ```bash
    cp .env.example .env
    ```

5. Générez la clé d'application Laravel :

    ```bash
    php artisan key:generate
    ```

6. Exécutez les migrations pour configurer la base de données :

    ```bash
    php artisan migrate
    ```

7. Lancez le serveur de développement :

    ```bash
    php artisan serve
    ```

8. Accédez à l'application via votre navigateur à l'adresse [http://localhost:8000](http://localhost:8000).

## Contribuer

Si vous souhaitez contribuer à ce projet, veuillez suivre les étapes suivantes :

1. Forkez le dépôt.
2. Créez une branche pour votre fonctionnalité ou correctif (`git checkout -b feature/your-feature`).
3. Effectuez vos modifications et ajoutez des commits (`git commit -am 'Add new feature'`).
4. Poussez votre branche (`git push origin feature/your-feature`).
5. Ouvrez une pull request sur GitHub.

## License

Ce projet est sous la licence [MIT](LICENSE).

## Contact

Si vous avez des questions, n'hésitez pas à me contacter à [ton-email@exemple.com](mailto:ton-email@exemple.com).
