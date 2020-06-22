# vuejs
test laravel 7 + vuejs

vue-laravel-crud
Vue 2.6 + Laravel 6 + Axios CRUD example app

See https://vuejsdevelopers.com/2018/02/05/vue-laravel-crud/ Inspiration from https://github.com/herusdianto/laravel-vue-crud

Installation
Clone repo

Change to directory

cd vue-laravel-crud
Install dependencies
composer install
Copy .env file
cp .env.example .env
Modify DB_* value in .env with your database config.

Generate application key:

php artisan key:generate
Migrate
php artisan migrate
Install Node modules
npm install
Build
npm run prod
(nếu có lỗi 
cài yarn install
xong chạy 
yarn run prod
)
Dummy Data
Open Tinker
php artisan tinker
Use factory script
factory(App\Crud::class, 3)->create();
