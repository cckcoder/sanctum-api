# Laravel API

## Note

* Create laravel project

    `composer create-project laravel/laravel <PROJECT_NAME>`

* Change MySql password

[Reset mysql password](http://localhost/dashboard/docs/reset-mysql-password.html)


* Listing route resource

    `php artisan route:list`

### Lib

[sanctum](https://laravel.com/docs/9.x/sanctum#installation)

## Create Model

* `php artisan make:model Product --migration`
* `php artisan migrate`

## Create Controller

* `php artisan make:controller ProductController --api`
