#SassyCoffee

An updated template that uses Sass and CoffeeScript along with Guard to provide a simple development environment for static websites that is compatible with Heroku.

##Requirements
- Ruby (prefereably 1.9.3, and using RVM will help you a lot)
    - install [RVM](http://beginrescueend.com/)
    - `rvm install 1.9.3`
    - `rvm use 1.9.3`
    - `rvm gemset create some-gemset-name`
    - `gem install bundler`

##Getting Started
1. `bundle install`
2. `guard init`
3. `bundle exec guard` (or `bundle exec guard &` to run in background).
4. Start writing CoffeeScript and Sass!

More info about using Guard [here](https://github.com/guard/guard#readme).