source 'https://rubygems.org'

ruby '1.9.3'
gem 'rails', '3.2.11'
gem 'json', '1.7.7'
gem 'jquery-rails'
gem 'omniauth-mygov', :git => 'https://github.com/GSA-OCSIT/omniauth-mygov.git'
gem 'devise'
gem 'rails_admin'
gem 'cancan'
gem 'will_paginate', '~> 3.0.3'
gem 'ransack', '~> 0.7.0'

group :development do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'haml-rails'
  gem 'quiet_assets'
end

group :production do
  gem 'mysql2'
end

group :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'simplecov', :require => false
  gem 'webmock'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end