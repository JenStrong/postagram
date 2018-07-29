# Postagram

## Overview
This project is a photo sharing app similar to Instagram. User's are able to post photos with descriptions and edit/delete posts. I built the login feature without a gem as a way to explore user authentication. This is my first solo Rails project and I'm currently working to include additional features like login and user profiles.  

## Process for creating User Sign Up
1. Created a User class with name, email and password attributes
2. Add validations for email address (checks that @ symbols is in correct place, length isn't too long)
3. Add validations for password (length isn't too short)
4. Use Rails build in function has_secure_password to set and authenticate against a BCrypt password
5. Create view for User Sign Up  

## Running the App
  Use Ruby 2.5.1
```
$ git clone https://github.com/JenStrong/postagram.git
$ cd postagram
$ bundle install
$ bin/rails db:setup
$ bin/rails server
```

## Running Tests
```
$ bin/rails test
```

## User Stories - completed
```
As a user,
So I can share my photography,
I would like to post an image to the site
```
```
As a user,
So I can give my friends more information,
I would like to add a description to my post
```
```
As a user,
So people know which posts are mine,
I would like to sign up
```

## User Stores - in progress
```
As a user,
So that I can revisit Postagram,
I would like to log in
```
```
As a user,
So that other people don't post on my account,
I would like to log out
```
```
As a user,
So I know who made each post,
I would like to see the name of the user next to their post
```
