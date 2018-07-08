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

1. Modeling Users:  Starting from scratch, in this chapter we created a working User model with name, email, and password attributes, together with validations enforcing several important constraints on their values. In addition, we have the ability to securely authenticate users using a given password. What I learned: Migrations allow us to modify our application’s data model.
Active Record comes with a large number of methods for creating and manipulating data models.
Active Record validations allow us to place constraints on the data in our models.
Common validations include presence, length, and format.
Regular expressions are cryptic but powerful.
Defining a database index improves lookup efficiency while allowing enforcement of uniqueness at the database level.
We can add a secure password to a model using the built-in has_secure_password method.

2. 
