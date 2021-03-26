# Installation guide

run:

`composer install`

`npm install`

create .env file with this command

`cp .env.example .env`

then run:

`php artisan key:generate`

then fill your database details in your .env file

now you can run migrations:

`php artisan migrate`

then start the application:

`php artisan serve`

and visit http://localhost:8000 to see the application.
