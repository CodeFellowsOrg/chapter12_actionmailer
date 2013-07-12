# Chapter 12: ActionMailer in Rails 3.2


### Initialize the Rails app

    git clone https://github.com/CodeFellowsOrg/chapter12_actionmailer.git
    cd chapter12_actionmailer
    gem install rails -v 3.2.13
    rails new .
    rails g scaffold user name:string email:string
    rake db:migrate
    rm public/index.html
