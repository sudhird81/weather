<p align="center"><a href="https://radiclehub.com" target="_blank"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRErCto1cd1ntxD4Lq9tGNwGZnDIWFW1Vd_hgyoj2knARfBCCcwSzzVxcPHQXAYs3lCmPQ&usqp=CAU" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Weather Dashboard

Weather Dashboard is for checking weather of any city as user input, We are using **weatherAPI** (https://www.weatherapi.com/) to fetch current weather information of a City:

-   First of all Make Sure you will have PHP running on your system, if not you can install XAMPP. Make Sure PHP is running via CLI too.
-   You need install **Composer** on your system Ref:(https://getcomposer.org/download/)
-   Once you install Composer, Install Laravel globally using command:

```
composer global require laravel/installer
```

Ref: [Read More on Laravel Installer](https://laravel.com/docs/7.x/installation#installing-laravel)

-   Get Clone of repository and pull the code from git using https://github.com/sudhird81/weather.git
-   Now from command line go to the root directory of the project **e.g. d:/project/weather/**
-   Install Dependiencies by running Command:

```
Composer Update
```

It will install the dependiences for Laravel framework. It may take some time

-   Once it's Done you can run it using command:

```
php artisan serve
```

it will run your application at http://127.0.0.1:8000/

Note: For now .env file is in the git repo, But we can keep it in gitignore. So make sure when you take pull you will have **WEATHER_API_KEY** in .env set

Screenshots:

<img src="https://sudhirdadwal.in/wp-content/uploads/images/laravel.png">
