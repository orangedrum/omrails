source 'https://rubygems.org'

ruby '2.0.0'
gem 'rails_12factor'
gem 'rails', '4.0.0'
gem 'sass-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'compass'
gem 'haml' # for SASS

#specify what gem to use in which enviroment
group :production do
	gem 'pg'
end

gem 'rails_12factor', group: :production

group :development do
	# Use sqlite3 as the database for Active Record
	gem 'sqlite3'
end


gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.0.0'

gem 'turbolinks'

gem 'jbuilder', '~> 1.2'

gem 'anjlab-bootstrap-rails', :require => 'bootstrap-rails',
                              :github => 'anjlab/bootstrap-rails'

gem "haml-rails", "~> 0.4"

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end