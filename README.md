# 環境構築

## Laravel インストール

curl を使ってインストール

```
curl -s "https://laravel.build/api" | bash
```

起動

```
cd api && ./vendor/bin/sail up
```

ローカルホストで起動していることを確認

マイグレーション

```
sail php artisan migrate
```

Breeze のインストール

```
sail composer require laravel/breeze --dev
```

API 用の scaffolding の作成

```
sail artisan breeze:install api
```
