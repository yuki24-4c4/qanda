# README

# 簡易Q&Aサイト

このリポジトリは Ruby on Rails を用いた簡易 Q&A サイトです。  
ローカル環境での構築方法を以下に示します。

## 環境構築手順

### 前提
- Ruby 3.4.5
- データベース: SQLite3（開発環境）

### 必要なソフトのインストール例（macOS/Linux）

#### rbenv と Ruby 3.4.5
```bash
# rbenv をインストール（macOS の場合）
brew install rbenv

# セットアップ
rbenv init

# リポジトリをクローン
git clone https://github.com/yuki24-4c4/qanda.git
cd qanda

# Ruby をインストール
rbenv install 3.4.5
rbenv global 3.4.5

# gemをインストール
bundle install

# データベースを構築
bin/rails db:migrate

# サーバーを起動
rails s

# URLにアクセス
http://127.0.0.1:3000/

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
