source 'http://rubygems.org'

gem 'rails'
gem 'jquery-rails'
gem 'tzinfo'
gem 'pg'
gem 'carrierwave'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-github'
gem 'kaminari'
gem 'airbrake'
gem 'draper'
gem 'fog'
gem 'simple_form'
gem 'girl_friday'
gem 'thin'
gem 'open4'
gem 'redcarpet'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'quiet_assets'
end

group :test, :development do
  gem 'pry-rails'
  gem 'awesome_print', :require => 'ap'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-jasmine-headless-webkit'
  gem 'jasmine-rails'
  gem 'cane'
  gem 'sqlite3'
end

group :test do
  gem "rake"
  gem 'simplecov', :require => false
  gem 'capybara', :require => false
  gem 'database_cleaner'
end

group :production do
  gem 'unicorn'
  gem 'dalli'
  gem 'mysql2'
  gem 'activerecord-mysql-adapter'
end
