
  
# Base laravel dashboard based on Laradminator
  
**_[Laravel](https://laravel.com/) PHP Framework with [Adminator](https://github.com/puikinsh/Adminator-admin-dashboard)_** as admin dash

## Setup:

#### Git clone
git clone https://github.com/m-nobre/laravel-adminator.git
#### Install backend dependencies
composer install 
#### Chmod Storage
sudo chmod 777 storage/ -R 
#### Enable link to storage
php artisan storage:link 
#### Update database credentials configuration
cp .env.example .env 
#### Generate new keys for Laravel
php artisan key:generate
#### Optional: Run migration and seed users and categories for testing
php artisan migrate:fresh --seed 
#### or npm i to Install node dependencies(>= node 9.x)
yarn install 
#### To compile assets for prod
npm run production 

```
