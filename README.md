```
rails _3.2.13_ new email_exercise --skip-test-unit
cd email_exercise
rails g scaffold user name:string email:string
rake db:migrate
rm public/index.html
git init 
git add .
git commit -m 'initial rails app with user scaffold'
```
