1)  Pour créer mon dossier
    - composer create-project symfony/website-skeleton tpSymfo "5.4.*" 
2) Pour créer User 
    - symfony console make:user
3) Le setup 
    - symfony console make:entity
    - User
4) création de Article et Comment
    - symfony console make:entity
        - Article
        - Comment
5) Création des relations 
    - symfony console make:entity
        - Article
            - comments
                - relation
                    - Comments
6) Création de la page HOME
    - symfony console make:controller
        - composer require annotation
7) Création du Register
    - symfony console make:registration-form
8)