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

# usage command
## host
**リポジトリ作成時はDockerfile, compose.ymlを一部コメントアウトしてコンテナが終了しないようにする**

- docker compose up -d
- docker exec -it complex-rails-web-1 /bin/bash

## docker
- bundle init
- bundle install
- bundle exec rails new .
