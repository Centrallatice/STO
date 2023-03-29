## Monter l'image avec sail

Via window powershell : executer dans le dossier du projet ./vendor/bin/sail up -d

## Lancer le serveur avec vite

Via window powershell : executer dans le dossier du projet npm run dev

## Exécuter les commandes artisans 
sail shell puis artisan migrate OU sail artisan migrate

## Vider le cache
sail artisan optimize

## Installer les permissions et rôles de base 
sail artisan db:seed --class=PermissionTableSeeder
sail artisan db:seed --class=CreateAdminUserSeeder

Par défaut les accès sont sto

## Documentations :

- Inertia : https://laravel.com/docs/9.x/starter-kits#breeze-and-inertia
- Laravel : https://laravel.com
- Sail : https://laravel.com/docs/9.x/sail
- Jetstream : https://jetstream.laravel.com/2.x/introduction.html
- Tailwind : https://tailwindcss.com/
- Laravel Breeze : https://github.com/laravel/breeze