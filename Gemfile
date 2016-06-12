source 'http://rubygems.org'

gem 'rails', '4.2.6'

gem 'geocoder', '1.1.8'
gem 'kaminari'

gem "mongo"
gem "mongoid", '~> 5.1.0'
gem 'mongoid-slug'#, :require => 'mongoid/slug'
gem 'bson_ext'
gem 'exifr', :git => 'git://github.com/picuous/exifr.git'

gem 'rails_autolink'

gem 'mongoid-paperclip', :require => "mongoid_paperclip"

group :development do
  gem 'wirble'
  gem 'capistrano'
  gem 'rack'
  gem 'rake'
  gem 'unicorn'
end

group :test, :development do
  gem "rspec-rails"
  gem "capybara"
  gem 'selenium-webdriver'
  gem 'factory_girl_rails'
  # gem 'debugger'
end

group :test do
  gem 'faker'
end
