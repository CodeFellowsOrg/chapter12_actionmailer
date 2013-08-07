# ActionMailer in Rails



### Initialize the Rails app

    git clone https://github.com/ryansobol/chapter12_actionmailer.git
    cd chapter12_actionmailer
    gem install rails -v 3.2.1
    rails new .
    rails g scaffold user name:string email:string
    rake db:migrate
    rm public/index.html
