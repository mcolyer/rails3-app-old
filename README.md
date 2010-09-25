A rails 3 application template which provides the gems I think are the best of breed.

** Authentication **

* devise

** Testing **

* rspec2
* capybara
* steak
* factory_girl

** Frontend **

* haml
* sass
* compass
* compass-susy
* jquery

## Getting started

```sh
rails my_app -J -T -m  http://github.com/mcolyer/rails3-app/raw/master/app.rb
cd my_app
gem install bundler
bundle install
script/rails generate rspec:install
```

## Origins

I have to admit, I didn't create this but started from this:
[[Blog post|http://blog.leshill.org/blog/2010/05/08/rails-3-rspec-factory-girl-haml-and-jquery.html]]
