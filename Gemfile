source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.5'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
gem 'redis-rails'
gem 'redis-namespace'
gem 'redis-rack-cache'
gem 'mock_redis'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'faraday'
gem 'faraday_middleware'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
gem 'fast_jsonapi'
gem 'figaro'
gem 'geocoder'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  gem 'pry'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'simplecov'
  gem 'shoulda-matchers'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'json'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
end

group :test do
  gem 'webmock'
  gem 'vcr'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
