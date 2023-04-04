source 'https://rubygems.org'
ruby '2.3.0'

gem 'rake', '>= 12.3.3'
gem 'thor'
gem 'pry', '~> 0.10.0'
gem 'activesupport', '~> 6.1', '>= 6.1.7.3', require: false
gem 'yajl-ruby', '>= 1.4.2', require: false

group :app do
  gem 'rack', '>= 3.0.0'
  gem 'sinatra', '>= 2.2.3'
  gem 'sinatra-contrib', '>= 2.2.3'
  gem 'thin'
  gem 'sprockets', '>= 4.2.0'
  gem 'sprockets-helpers'
  gem 'erubis'
  gem 'browser'
  gem 'sass'
  gem 'coffee-script'
end

group :production do
  gem 'uglifier'
end

group :development do
  gem 'better_errors', '>= 2.8.0'
end

group :docs do
  gem 'typhoeus'
  gem 'nokogiri', '>= 1.13.9'
  gem 'html-pipeline', '>= 2.4.2'
  gem 'progress_bar', require: false
  gem 'unix_utils', require: false
  gem 'tty-pager', require: false
end

group :test do
  gem 'minitest'
  gem 'rr', require: false
  gem 'rack-test', require: false
end

if ENV['SELENIUM'] == '1'
  gem 'capybara'
  gem 'selenium-webdriver'
end
