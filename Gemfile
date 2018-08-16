if RUBY_VERSION =~ /1.9/
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end

source 'http://gems.ruby-china.com'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.3.3'

###BASEIC###
gem 'rails', '~> 5.2.1'
gem 'tzinfo-data'

#which is activesupport depended 
gem 'concurrent-ruby', '~> 1.0', '>= 1.0.5'
gem 'i18n', '~> 1.1'
gem 'tzinfo', '~> 1.2', '>= 1.2.5'
gem 'minitest', '~> 5.11', '>= 5.11.3'

#which is activesupport running Necessity
gem 'will_paginate', '~> 3.1', '>= 3.1.6' #must newest 

#which is boot.rb running depended 
gem 'bootsnap', '~> 1.3', '>= 1.3.1'

gem 'builder','3.2.3'
gem 'rack','2.0.5'
gem 'bootstrap-sass', '2.0.0'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.9.1' #must newest which can compatible il8n
gem 'bootstrap-will_paginate', '0.0.6'
gem 'nokogiri','1.8.4'

group :development do
  gem 'sqlite3', '1.3.13'
  gem 'annotate', '~>2.4.1.beta'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '5.0.7'
  gem 'coffee-rails', '4.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '~> 4.3.3'

group :test, :development do
  gem 'rspec-rails', '3.8.0'
  gem 'guard-rspec', '4.7.3'
  gem 'guard-spork', '2.1.0'
  gem 'spork', '0.9.0'
end

group :test do
  gem 'capybara', '~> 3.6'
  gem 'rb-fchange', '0.0.5'
  gem 'rb-notifu', '0.0.4'
  gem 'win32console', '1.3.0'
  gem 'factory_girl_rails', '4.9.0'
  gem 'cucumber-rails', '1.2.1', require: false
  gem 'database_cleaner', '0.7.0'
end

group :production do
  gem 'pg', '0.12.2'
end


###EXTEND###
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# Use ActiveStorage variant
gem 'mini_magick', '~> 4.8'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'duktape'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.1', '>= 5.1.1'
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

# Use Capistrano for deployment
gem 'capistrano-rails', group: :development

group :test do
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome：##EXTEND###
  gem 'chromedriver-helper'
end
  