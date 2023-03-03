<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# SSO Laravel

Info: https://www.youtube.com/watch?v=kRGPKh3NgHU&list=PLC-R40l2hJfdyfZ3jkDKOcyoqmIgw2wda

## SSO
* Modificare `.env`
```
  php artisan config:cache
  php artisan migrate
  php artisan passport:install --uuids [--force] # force se si desidera, e in tal caso rispondere al prompt con 'yes'

```
* Va registrato un utente per ogni client tramite pulsante 'Register'
```
php artisan passport:client #salvare credenziali e redirect_uri
```


## CLIENT
Piccolo client di test. Vedasi relativa repository.
* composer update se necessario
* Modificare `.env` e 
``` php artisan config:cache ```
