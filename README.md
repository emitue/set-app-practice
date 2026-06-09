# set-app practice

## 概要

COACHTECH 教材 Tutorial 9-1「環境構築ハンズオン」で作成した成果物です。
Laravel Sail と Docker を使って、Tutorial 9~10 のハンズオンで使う開発環境を構築しました。

## 使用技術

- PHP 8.x
- Laravel 10.x
- Laravel Sail（Docker Compose）
- MySQL, phpMyAdmin

## 学んだこと

- Laravel Sail を使った Docker ベースの開発環境構築
- compose.yaml の構造と、phpMyAdminサービスの追加
- php artisan key:generate でアプリケーションキーを生成する役割
- sail 起動時（./vender/bin/sail up -d）エラー：80番ポートを既に別のコンテナが使用しているため、新しいLaravelプロジェクトが起動できない 発生したため、docker desktopの他のプロジェクトを全て停止。

## 開発環境

- Laravel
- PHP 8.x
- MySQL 8.4
- Docker
- phpMyAdmin

## 起動方法

```bash
docker compose up -d
```

## Laravelへアクセス

http://localhost

## phpMyAdminへアクセス

http://localhost:8080

## 学習内容

- Docker環境構築
- Laravel基礎
- MySQL操作
- Git/GitHub
