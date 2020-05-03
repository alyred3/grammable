# Grammable

An Instagram clone built using Test Driven Development.

[View the deployed application](https://grammable-alyssa-redman.herokuapp.com/grams)

____________

### Features

* Ruby 2.5.3

* Test Driven Development using Rspec and FactoyBot gems

* PostgresSQL database

* Devise for user authentication

* Simple Form gem 

* Amazon Web Service (AWS) for image storage

* Figaro gem for secure configuration

* CarrierWave for file uploads

* MiniMagic gem for image resizing

____________

### Installation

From this repository click <b>Clone or download</b> and copy clone command for SSH `git@github.com:alyred3/grammable.git` or HTTPS `https://github.com/alyred3/grammable.git`

From terminal window change to local directory where you want to clone repo

Paste clone command into command line `$git clone git@github.com:alyred3/grammable.git` or `$git clone https://github.com/alyred3/grammable.git`

Run `$ bundle install`

Run `$ bundle exec figaro install` to add `config/application.yml`  to add to your `.gitignore`

Add AWS keys to `config/application.yml` to congifure application to connect to you Amazon S3 account for image uploading

____________

### How to use 

#### Sign up to create an account
![Screenshot](app/assets/images/signup.gif)

#### Post new photos
![Screenshot](app/assets/images/new.gif)

#### Add comments
![Screenshot](app/assets/images/comment.gif)

#### Edit and destroy
![Screenshot](app/assets/images/editdestroy.gif)








