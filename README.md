# laravel-MikrotikAPI

A working Laravel sample using a number of Composer and NodeJS plugins to access Mikrotik RouterOS API over the network and show some useful information in table views.

## Deployment

```bash
git clone https://github.com/johanels/laravel-MikrotikAPI.git
npm install
composer install
cp .env.sample .env
vi .env
php artisan key:generate
npm run development
php artisan serve
```

## References

* Mikrotik RouterOS API - https://wiki.mikrotik.com/wiki/Manual:API
* Laravel - https://laravel.com
* NodeJS - https://nodejs.org
* Composer - https://getcomposer.org
* krok/routeros-api - https://packagist.org/packages/krok/routeros-api
* DataTables.net - https://datatables.net
