source 'https://rubygems.org'
ruby '2.3.0'

gem 'rake'
gem 'thor'
gem 'pry', '~> 0.10.0'
gem 'activesupport', '~> 4.2', require: false
gem 'yajl-ruby', require: false

group :app do
  gem 'rack', '>= 2.2.8.1'
  gem 'sinatra', '>= 2.0.0'
  gem 'sinatra-contrib', '>= 2.0.0'
  gem 'thin', '>= 1.7.1'
  gem 'sprockets', '>= 3.6.1'
  gem 'sprockets-helpers', '>= 1.2.2'
  gem 'erubis'
  gem 'browser'
  gem 'sass'
  gem 'coffee-script'
end

group :production do
  gem 'uglifier'
end

group :development do
  gem 'better_errors', '>= 2.2.0'
end

group :docs do
  gem 'typhoeus'
  gem 'nokogiri', '>= 1.15.6'
  gem 'html-pipeline', '>= 2.4.2'
  gem 'progress_bar', require: false
  gem 'unix_utils', require: false
  gem 'tty-pager', require: false
end

group :test do
  gem 'minitest'
  gem 'rr', require: false
  gem 'rack-test', '>= 0.7.0', require: false
end

if ENV['SELENIUM'] == '1'
  gem 'capybara'
  gem 'selenium-webdriver'
end
