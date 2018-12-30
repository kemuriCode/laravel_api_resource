<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Make Laravel Resource (demo)

>Laravel 5.7 API that uses the API resources. This is an API for an article CRUD app

### Task List

- [x] create laravel project

`composer create-project laravel/laravel MyProject --prefer-dist`
- [x] set access to folders


- [x] install dependencies

`composer install`

- [x] run migrations

`php artisan migrate`

- [x] import articles

`php artisan db:seed`

- [x] add virtual host if using Apache

- [x] list all articles with links and meta

``` bash
GET api/articles
```
- get single article
``` bash
GET api/article/{id}
```

- delete article
``` bash
DELETE api/article/{id}
```

- add article
``` bash
POST api/article
title/body
```

- update article
``` bash
PUT api/article
article_id/title/body
```

## App Info

### Author
Marcin Dymek

[My Website] (https://t0shifollow.github.io/portfolio)

### Version

1.0.0

### License

This project is licensed under the MIT License
