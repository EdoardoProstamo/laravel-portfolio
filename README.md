# Sito Portfolio
- Creazione passo dopo passo di un sito portfolio online.

## DAY-1
#### Per iniziare, mettiamo su un'app Laravel provvista di autenticazione grazie a Breeze:
- Avviamo l'installazione di Laravel
- Installiamo Breeze e Bootstrap
    - Inseriamo i comandi:
        - composer require laravel/breeze --dev
        - php artisan breeze:install
            - blade
            - yes
            - PHPUnit
        - composer require pacificdev/laravel_9_preset
        - php artisan preset:ui bootstrap --auth
        - npm i
        - npm run dev
- Verifichiamo che l'autenticazione funzioni
- Creiamo un layout per la nostra area admin