# 1. Technology
- PHP >= 7.3
- Laarvel Framework 8.x
- XML PHP Extension
- OpenSSL PHP Extension
- PDO PHP Extension

# 2. Configuration requirements
- Install composer: https://getcomposer.org/

# 3. Running

## Clone repo

```
$ git clone https://github.com/TanHongIT/jena-ecommerce
$ cd jena-ecommerce
```

## Composer & npm

Run:

```
$ npm install
$ composer install
```

## Create APP_KEY

Run:

```
$ php artisan key:generate
```

## Create a new database in your host & edit .env

Create a new database in your server and edit the information in the .env file

```laravel
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=jena-ecommerce
DB_USERNAME=root
DB_PASSWORD=
```