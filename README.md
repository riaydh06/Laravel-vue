# Laravel-vue

Clone repo

Change to directory

cd vue-laravel-crud

Install dependencies

composer install

Copy .env file

cp .env.example .env

Modify DB_* value in .env with your database config.

Generate application key:

php artisan key:generate

Migrate

php artisan migrate

Install Node modules

npm install

Build

npm run prod

Dummy Data

Open Tinker

php artisan tinker

Use factory script

factory(App\Crud::class, 3)->create();
