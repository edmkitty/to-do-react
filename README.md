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

## Setup

For some reason, making a new rails app did not automatically install webpacker or react. I had to change my node version to something newer, and then run the following commands:

`rails webpacker:install`
`rails webpacker:install:react`