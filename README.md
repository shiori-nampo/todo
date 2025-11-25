# Todoアプリ

# 概要
Laravelで作ったTodo管理アプリです。
Todoの作成・更新・削除とカテゴリ管理ができます。

## 開発環境
- PHP 7.3以上
- Laravel 8.75以上
- MySQL

## 実行方法
1. リポジトリをクローン
2. composer install
3. .env を設定（DB接続）
4. php artisan migrate
5. php artisan serve

## 機能
- Todo 作成・更新・削除
- カテゴリ作成・更新・削除
- カテゴリ別での検索

## ER図
[ER図](doc/er_diagram.drawio)
(※このER図はGitHub上では直接表示できません。VScodeやdraw.ioで開いて確認してください)