source 'http://rubygems.org'

gem 'rails', '3.2.14'
gem 'active_attr'
gem 'mysql2', '~> 0.3.21'
gem 'jquery-rails'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'capistrano'
gem 'stringex'
gem 'nokogiri'
gem 'delayed_job_active_record'
gem 'will_paginate', '~> 3.0'
gem 'will_paginate-bootstrap'
gem "delayed_job_admin", :git => "https://github.com/ngnam/delayed_job_admin.git", :branch => "master"

group :octopress do
  gem 'rake', '12.3.1'
  gem 'rack'
  gem 'jekyll', :git => "https://github.com/ngnam/jekyll.git", :branch => "master"
  gem 'rdiscount'
  gem 'pygments.rb'
  gem 'RedCloth'
  gem 'haml', '>= 3.1'
  gem 'compass', '>= 0.11'
  gem 'rubypants'
  gem 'rb-fsevent'
  gem 'stringex'
  gem 'liquid', '4.0'
  gem 'mini_magick'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
  gem 'bootstrap-sass', '2.0.1' #momentarily sticking with 2.0.1 due to icon display issue
end

gem "rspec-rails", "~> 2.6", :group => [:test, :development]

group :test do
  gem 'capybara'
  gem "factory_girl_rails"
  gem 'launchy'
end
