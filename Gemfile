source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.0'

# FOUNDATION
gem 'rails', '6.1.7.3'
gem 'dotenv-rails', '>= 2.7.6', require: 'dotenv/rails-now'
gem 'pg', '>= 0.18', '< 2.0'
gem 'coffee-rails', '~> 4.2', '>= 4.2.2'
gem 'webpacker'

# PERFORMANCE
gem 'bootsnap', '>= 1.1.0', require: false
gem 'dalli', '>= 3.2.3'
gem 'memcachier'
gem 'turbolinks', '~> 5'
gem 'puma', '~> 4.3', '>= 4.3.12'
gem 'sass-rails', '~> 6.0', '>= 6.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'sinatra', '>= 2.2.3', :require => nil # for sidekiq UI
gem 'sidekiq-status'
gem 'sidekiq', '>= 7.0.0'
gem 'redis-rails'
gem 'redis-objects'
gem 'redis-namespace'

# TOOLS
gem "sentry-raven"
gem 'devise'
gem 'jbuilder'
gem 'rack-cors', :require => 'rack/cors'
gem 'postmark-rails'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'letter_opener'
  gem 'rspec-rails', '~> 3.6.1'
  gem "factory_bot_rails", "~> 4.10.0"
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'rename'
  gem "better_errors", ">= 2.8.0"
  gem "binding_of_caller"
  gem 'web-console', '>= 4.0.1'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'spring-commands-rspec'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.32.0'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
  gem 'database_cleaner-active_record'
  gem 'shoulda-matchers', '~> 4.4', '>= 4.4.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
