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