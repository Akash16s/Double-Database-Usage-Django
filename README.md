# TradexaApp
App for the internship selection test

## Two apps with two different database
default -- blog
db_app1 -- product

## App Blog
It it a HTML Render application

## App Product 
It is a REST API APP

## Task
Create an application that has two apps. 
1. User with user and Post model
    User : first_name, last_name, email, password, username
    Post : user, text, created_at, updated_at
   Foreign key relationship exists between User and Post on Model level not on Database level.
2. Products app with Product model.
    Product : name, weight, price, created_at, updated_at

Both of the apps should use two different databases.

Create a form that an authenticated user can use to create a post.
Note: Register all models on admin dashboard.

** Not included higher order functionality because of the target provided.
