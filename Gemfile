source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.1'


gem 'puma', '~> 3.11'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'jbuilder', '~> 2.5'
gem 'owlcarousel-rails', '~> 2.2', '>= 2.2.3.5'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'newrelic_rpm'

group :development, :test do
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
 
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do

  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'

  gem 'chromedriver-helper'
end

group :production do
  gem 'pg', '~> 1.1', '>= 1.1.3'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
