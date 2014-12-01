source 'https://rubygems.org'

ruby '2.1.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.7'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

gem 'rack-mini-profiler'

gem 'slim-rails'
gem 'dotenv-deployment'

gem 'devise'
gem 'cancancan'

gem 'simple_form', '~> 3.1.0.rc2'
gem 'twitter-bootstrap-rails'

gem 'kaminari'
gem 'kaminari-bootstrap'

gem 'inherited_resources'

gem 'grape'
gem 'grape-entity'

gem 'honeybadger'

gem 'phony_rails'

gem 'pusher'

gem 'newrelic_rpm'

group :development do
  gem 'spring'
  gem 'guard'
  gem 'guard-rspec', require: false
  gem 'guard-bundler', require: false
  gem 'spring-commands-rspec'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
  gem 'quiet_assets'
  gem 'rubocop', require: false
  gem 'guard-rails'
  gem 'bullet'
end

group :development, :test do
  gem 'factory_girl_rails', '~> 4.5'
  gem 'awesome_print', git: 'git://github.com/michaeldv/awesome_print.git'
  gem 'rspec-rails', '~> 3.1.0'
  gem 'pry-rails'
  gem 'launchy'
  gem 'database_cleaner', require: false
  gem 'shog'
  gem 'letter_opener'
  gem 'faker'
  gem 'brakeman', require: false
end

group :production do
  gem 'passenger'
  gem 'rails_12factor'
end

group :test do
  gem 'guard-migrate', require: false
  gem 'shoulda-matchers', require: false
  gem 'webmock', require: false
  gem 'simplecov', require: false
end
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
