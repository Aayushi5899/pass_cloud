# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
- 

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
Part1 Setting up Heroku Account

    Go to https://dashboard.heroku.com
    Create Account with college Email and enter your details.
    Account create
    Now, need to create an application so click on New app
    Enter application name like web401cloudserver
    region and Enter

Part2 Deployment

    Create or login to your Github account

    Create a Repository name like web401cloud_serverPaas

    Pull the repository to github desktop

    Open githib desktop and upload the given file on the created repostiory

    Now, open Heroku and open the web401cloudserver.

    in Deployment method change to github from heroku git

    Connect your Github account

    Add the created repository (web401cloud_serverPaas)

    Automatic deployment enable

Part3 Setup

    In the more button on the top right hand side
    Run Console
    rake db:migrate
    rake db:seed
    App is available

my applicaton link https://web401cloudserver.herokuapp.com/