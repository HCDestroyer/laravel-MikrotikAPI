# laravel-MikrotikAPI

A working Laravel working sample using a number of Composer and NodeJS plugins to access Mikrotik RouterOS API over the network and show some useful information in table views.

## Deployment

```bash
git clone https://github.com/johanels/laravel-MikrotikAPI.git
npm install
composer install
cp .env.example .env
vi .env
php artisan key:generate
npm run development
php artisan serve
```
