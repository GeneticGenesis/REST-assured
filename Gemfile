source "https://rubygems.org"

ruby '2.2.1'

gemspec

gem 'pg'

# skipped for heroku
group :test do
  gem 'cucumber'
  gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'rspec'
  gem 'shoulda-matchers', require: false
  gem 'anticipate'
  gem 'rack-test'
  gem 'capybara'
  gem 'rake'
  #gem 'mysql2'
  gem 'sqlite3'
  gem 'chromedriver-helper'
  gem 'simplecov'
  gem 'awesome_print'
end

# skipped for heroku and travis
group :development do
  gem 'relish'
  gem 'pry'
  gem 'pry-byebug'
  gem 'launchy'
end

