# docker-laravel-handson
laravelのプロジェクトを作成するためのテンプレート
## 構成要素
 - app php
 - web nginx
 - db mysql
 
## 環境構築方法
1. `git clone git@github.com:yu-tooo/docker-laravel-handson.git`
2. `cd docker-laravel-handson`
3. `cd src`
4. `cp .env.example .env`
5. `chmod -R 777 storage bootstrap/cache`
6. `composer install`
7. `php artisan key:generate`
8. `php artisan storage:link`
