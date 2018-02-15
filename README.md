## Server Requirements
- PHP >= 7.1.3
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- Ctype PHP Extension
- JSON PHP Extension

Directories within the ***storage*** and the ***bootstrap/cache*** directories should be writable by your web server.

Create your own ***.env*** file based in the ***.env.example***.

## Installing
```sh
composer install && php artisan key:generate && php artisan jwt:secret
```

## Running
```sh
php artisan serve
```
