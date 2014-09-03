source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.8'
gem 'bootstrap-sass', '2.3.2.0'
gem 'sprockets', '2.11.0'
gem 'pg', '0.15.1'

# Use sqlite3 as the database for Active Record
group :development, :test do
	gem 'rspec-rails', '2.13.1'
	gem 'guard-rspec', '2.5.0'
	gem 'spork-rails', '4.0.0'
	gem 'guard-spork', '1.5.0'
	gem 'childprocess', '0.3.6'
end

group :test do 
	gem 'selenium-webdriver', '2.35.1'
	gem 'capybara', '2.1.0'
	gem 'growl', '1.0.3'
end



gem 'sass-rails', '4.0.1'# Use SCSS for stylesheets
gem 'uglifier', '2.1.1'# Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '4.0.1'# Use CoffeeScript for .js.coffee assets and views
gem 'jquery-rails', '3.0.4'# Use jquery as the JavaScript library
gem 'turbolinks', '1.1.1'# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jbuilder', '1.0.2'# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

group :doc do
  gem 'sdoc', '0.3.20', require: false # bundle exec rake doc:rails generates the API under doc/api.
end

group :production do 
	
	gem 'rails_12factor', '0.0.2'
end
