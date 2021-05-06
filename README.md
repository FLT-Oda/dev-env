# 環境構築
## 環境
- docker 20.10.2
- nginx
- php7.4
- mysql8.0
- composer 2.0.13

## セットアップ手順
1. docker-compose.ymlのあるディレクトリで下のコマンドを実行する
   `docker-compose up -d`
2. phpコンテナの中に入る
   `docker exec laravel_app_1 -it bash`
3. /var/www/htmlに移動する
4. Laravelのプロジェクトを下記のコマンドで作成する
   `composer create-project --prefer-dist laravel/laravel my-laravel-app`
