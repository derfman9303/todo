# Documentation

## What this app is:

This single-page to-do application features a fluid user interface that– by using JavaScript– allows users to rapidly add dynamic content.

You may visit the deployed version [here](https://todo-frederic-hodges.herokuapp.com/).

![Todo app screenshot](app/assets/images/todo.PNG "todo app screenshot")

***
# Setup

## Prerequisites:
 
 The following tools should be installed on the system before following setup steps.
 
  - Git
  - Ruby 2.5.3
  - Rails 5.2.3
  
1. **Clone repo:**
       
        git@github.com:derfman9303/todo.git
        
2. **On the command line, navigate to the Splurty directory**
        
        cd todo

3. **Create the database**
        
        rails db:create db:migrate
        
4. **Install gems**
        
        bundle install

***
# Usage

## Start your server:

        rails server -b 0.0.0.0 -p 3000

You may now visit your app at http://localhost:3030


***
# Deployment

## Pushing to Heroku

If you would like, you may push your app up to Heroku by running the following commands:

        git init
        
        git add .
        
        git commit -am "initial commit"
        
        heroku create
        
        git push heroku master
 
