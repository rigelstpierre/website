source 'https://rubygems.org'
ruby "2.0.0"

gem 'haml-rails'
gem 'jquery-rails'
gem 'pg'
gem 'rails', '3.2.13'
gem 'thin'
gem 'bugsnag'
gem 'rack-rewrite'
gem 'devise'
gem 'rMeetup', :git => 'git://github.com/tannermares/rmeetup.git'
gem 'figaro'
gem 'dalli'
gem 'newrelic_rpm'

group :production do
  gem 'rack-google-analytics', :require => 'rack/google-analytics'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'factory_girl_rails', '~> 4.0.0'
  gem 'guard'
  gem 'guard-spork'
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'mailcatcher'
  gem 'rb-fsevent'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'meta_request'
  gem 'fakeweb'
  gem 'pry-rails'
  gem 'quiet_assets'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  gem 'compass-rails'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'uglifier', '>= 1.0.3'
  gem 'bootstrap-sass', '~> 2.3.1.0'
end