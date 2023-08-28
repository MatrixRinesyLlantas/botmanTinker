# BotMan Tinker

Esta libreria te permite probar tu chatbot en una terminal local.

## Instalacion

Ejecuta `matrix-rines-y-llantas/botman-tinker` para agregar la libreria a tu proyecto de laravel.

Despues en tu archivo `config/app.php` agrega la siguiente linea:

```php
BotMan\Tinker\TinkerServiceProvider::class,
```

dentro del arreglo(array) de `providers`.

## Uso

Ahora solo tienes que ejecutar el nuevo comando en tu terminal y podras pobrar tu chatbot localmente:

```php
php artisan botman:tinker
```

## Licencia

BotMan y Tinker es un software gratuito distribuido bajo los terminos de la licencia MIT.
