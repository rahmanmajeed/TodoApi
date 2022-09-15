<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Setup Project

1. clone this repo to your `htdocs` folder-

```sh
git clone git@github.com:rahmanmajeed/TodoApi.git

```

2. install composer package for this by-

```sh
composer install
```

3. copy or rename `.env.example` file to `.env`

4. create a database named as `todoapi`

5. run laravel migration command

```sh
php artisan migrate
```

6. create two demo task by -

```sh
php artisan db:seed
```

7. at last run the project by-

```sh
php artisan serve
```
