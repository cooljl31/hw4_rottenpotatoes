source 'http://rubygems.org'

gem 'rails', '5.0.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'ruby-debug19', :require => 'ruby-debug'
  gem 'cucumber-rails', '>= 1.3.0'
  gem 'cucumber-rails-training-wheels', '>= 1.0.0'
  gem 'database_cleaner'
  gem 'capybara', '>= 1.1.2'
  gem 'launchy'
  gem 'rspec-rails', '>= 2.8.1'
  gem 'simplecov'
end
group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'therubyracer'              
  gem 'sass-rails', '~> 5.0.5'
  gem 'coffee-rails', '~> 4.1.1'
  gem 'uglifier'
end

gem 'jquery-rails', '>= 4.0.1'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
gem 'haml'
