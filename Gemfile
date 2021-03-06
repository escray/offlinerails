source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.3'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Gemfile from anndoko@github #
# Gemfile from zuodao@github #
# user count #
gem 'devise'

# UI #
gem 'bootstrap-sass'
gem 'bootstrap-tagsinput-rails'
gem 'simple_form'
gem 'will_paginate'
gem 'will_paginate-bootstrap'
gem 'font-awesome-rails'
gem 'masonry-rails'
gem 'material_icons'

# search #
gem 'ransack'

# picture #
gem 'carrierwave'
gem 'carrierwave-aws'
gem 'mini_magick'

# order status #
gem 'aasm'

# AWS #
gem 'fog-aws'
gem 'figaro'

# social share #
gem 'social-share-button'
gem 'seo_helper'
gem 'omniauth-google-oauth2'
gem 'omniauth-facebook'
gem 'omniauth-github'

# Intercom Customer Service #
gem 'intercom-rails'

# PayPal interface #
gem 'braintree'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'pry'
  # Rails Console layout
  gem 'awesome_rails_console'

  # gem 'sqlite3'

  gem 'annotate'
  gem 'dotenv-rails'
  gem 'letter_opener'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  # gem 'spring'
  # gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
