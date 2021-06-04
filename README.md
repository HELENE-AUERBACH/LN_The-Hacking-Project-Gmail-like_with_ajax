# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

ruby 2.7.1p83 (2020-03-31 revision a0c7c23c9c) [x86_64-linux]

* Rails version

Rails 5.2.3

* Configuration

rm ln-to_do_list_with_ajax/Gemfile.lock

$ gem uninstall rails
(=> 3. All versions)

$ gem uninstall railties
(=> 3. All versions => y, then Y)

$ cd ln-to_do_list_with_ajax

ln-to_do_list_with_ajax$ bundle install

ln-to_do_list_with_ajax$ rails -v
(=> Rails 5.2.3)

1. En ce qui concerne l'environnement de développement :

* Database creation

ln-to_do_list_with_ajax$ RUBYOPT='-W:no-deprecated -W:no-experimental' rails db:create

ln-to_do_list_with_ajax$ RUBYOPT='-W:no-deprecated -W:no-experimental' rails db:migrate

* Database initialization

ln-to_do_list_with_ajax$ RUBYOPT='-W:no-deprecated -W:no-experimental' rails db:seed

* How to run the test suite

ln-to_do_list_with_ajax$ RUBYOPT='-W:no-deprecated -W:no-experimental' rails server (=> http://localhost:3000 )

2. En ce qui concerne l'environnement de production :

ln-to_do_list_with_ajax$ heroku run rails db:migrate

* Deployment instructions

ln-to_do_list_with_ajax$ heroku ps:scale web=1

* Database initialization

ln-to_do_list_with_ajax$ heroku run rails db:seed

* How to run the test suite

ln-to_do_list_with_ajax$ heroku open (=> https://ln-thp-ln-to_do_list_with_ajax.herokuapp.com )

