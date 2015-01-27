source 'https://rubygems.org'


gem 'rails', '3.2.17'

gem 'jquery-rails'
gem 'omniauth-twitter'
gem 'rest-client'
gem 'rails_config'
gem 'newrelic_rpm'
gem 'unicorn'
gem 'rails_12factor'
gem 'bootstrap-sass'

group :development, :test do
	gem 'rspec-rails'
end

group :development, :test, :herokuproduction do
	gem 'thin'
end

group :development, :test, :production do
	gem 'sqlite3'
end

group :assets do
	gem 'sass-rails'
	gem 'coffee-rails'
	gem 'uglifier'
end

group :test do
	gem 'capybara', '1.1.2'
	gem 'webmock'
end

group :herokuproduction do
	gem 'pg'
end

