
  
#Base laravel dashboard based on Laradminator
  
**_[Laravel](https://laravel.com/) PHP Framework with [Adminator](https://github.com/puikinsh/Adminator-admin-dashboard)_** as admin dash

## Setup:

After cloning, 

composer install # Install backend dependencies

sudo chmod 777 storage/ -R # Chmod Storage

php artisan storage:link # Enable link to storage

cp .env.example .env # Update database credentials configuration

php artisan key:generate # Generate new keys for Laravel

php artisan migrate:fresh --seed # Run migration and seed users and categories for testing

yarn install # or npm i to Install node dependencies(>= node 9.x)

npm run production # To compile assets for prod

```
