## [Building a Laravel 10 Application with Vue 3](https://laraveltuts.com/building-a-laravel-10-application-with-vue-3-complete-guide-to-crud-operations/)

1.  create a new Laravel project
```
composer create-project laravel/laravel l10-ui-vue3
```
2.  Creating the Model, Migration, and Controller. Implementing CRUD Operations in the API and test with Postman.
```
php artisan make:model Product -mcr
php artisan migrate
```    
3.  install the frontend scaffolding using the `laravel/ui` with `bootstrap 5.2` and `vue3`
```
composer require laravel/ui
php artisan ui vue
set bootstrap@5.0 in package.json
npm install 
<!-- npm uninstall bootstrap -->
<!-- npm install bootstrap@5.0 -->
npm install vue-router
npm run build
```
4.  Implementing CRUD Operations in Vue 3. Update the `welcome.blade.php` file, which will be SPA
