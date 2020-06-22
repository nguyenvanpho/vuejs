# vuejs
test laravel 7 + vuejs

vue-laravel-crud
Vue 2.6 + Laravel 6 + Axios CRUD example app

See https://vuejsdevelopers.com/2018/02/05/vue-laravel-crud/ Inspiration from https://github.com/herusdianto/laravel-vue-crud

1:Installation
Clone repo

2:Change to directory

cd vue-laravel-crud

3:Install dependencies

composer install

4:Copy .env file

cp .env.example .env

5:Modify DB_* value in .env with your database config.

6:Generate application key:

php artisan key:generate

7:Migrate

php artisan migrate

8:Install Node modules

npm install
Build
npm run prod
(nếu có lỗi 
cài yarn install
xong chạy 
yarn run prod
)

9:Dummy Data

Open Tinker
php artisan tinker
Use factory script
factory(App\Crud::class, 3)->create();
