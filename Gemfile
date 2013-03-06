source 'https://rubygems.org'

gem 'rails', '3.2.11'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem "pg", '0.14.1'

gem "devise"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
	gem 'jquery-rails'
	gem 'sass-rails',   '~> 3.2.3'
	gem 'coffee-rails', '~> 3.2.1'
	gem 'compass-rails'
	gem 'therubyracer', :platform => :ruby
	gem "twitter-bootstrap-rails"
	gem "less-rails"
	gem 'uglifier', '>= 1.0.3'
end



group :production do
	gem "exception_notification"
	gem "unicorn", :platforms => :ruby
	gem "therubyracer"
end

group :development do
	gem "capistrano"
	gem "letter_opener"
	gem 'thin'
end
