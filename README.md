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
# RubyOnRails_DevcampPortfolio

Rails version: 6.0.1
Ruby version: ruby 2.6.5p114 (2019-10-01 revision 67812) [x86_64-darwin18]

```terminal
rails new DevcampPortfolio -T --database=postgresql
rails db:create
rails db:migrate
rails s
```

```terminal
rails g scaffold Blog title:string body:text
rails db:migrate
```
g - generate \
scaffold - create multiple things at once

db/schema.rb \
added to db/migrate folder
