# README

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

# refrigerator DB設計
## usersテーブ
|Column|Type|Options|
|------|----|-------|
|password|string|null: false|
|username|string|null: false|
### Association
- has_many :puts

## putsテーブル
|Column|Type|Options|
|------|----|-------|
|title|string|null: false|
|image|string|null: false|
### Association
- belongs_to : user

