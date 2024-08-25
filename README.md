# TODOリスト
<img width="1512" alt="スクリーンショット 2024-08-25 17 57 13" src="https://github.com/user-attachments/assets/fe2298b2-760b-407b-898f-d70eb12a0512">


## 環境構築
### Dockerビルド

1.git clone git@github.com:coachtech-material/laravel-docker-template.git

2.docker-compose up -d --build

### Laravel環境開発

1.docker-compose exec php bash

2.composer install

3..env.exampleファイルから.envを作成し、環境変数を変更

4.php artisan key:generate

5.php artisan migrate

6.php artisan db:seed



## 使用技術(実行環境)
- php8.0
- laravel10.0
- MySQL8.0

## ER図


## URL
- 開発環境：http://localhost/
- phpMyAdmin:http://localhost:8080/
