## Simple Laravel 10 REST API

Simple Laravel 10 REST API with Sanctum Registration/Authentication, Products + Categories.
Простой Ларавель 10 Рест АПИ с регистрацией, аутентификацией, продукты и категории

Install:
- Запустим докер
- перейдем в папку и запустим composer update
- ./vendor/bin/sail up

В докер контейнере:
- php artisan key:generate
- php artisan migrate
- php artisan queue:work (For queues)


API Structure:
CRUD[GET, POST, PUT/PATCH, DELETE] for Categories and Products
[POST] Login / Register 

