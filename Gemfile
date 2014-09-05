# A Gemfile describes the gem dependencies required to execute associated Ruby code.

# source repository for gems listed below
source 'https://rubygems.org'

# identifying the Ruby version expected by the application
ruby '2.0.0'

# gem requirements
gem 'rails', '4.0.8'

# this gem included only in a development environment (prevents potential conflicts with database used by Heroku)
group :development do
  gem 'sqlite3', '1.3.8'
end

gem 'sass-rails', '4.0.3'    # use SCSS for stylesheets
gem 'uglifier', '2.1.1'      # use Uglifier as compressor for Javascript assets
gem 'coffee-rails', '4.0.1'  # use CoffeeScript for .js.coffee assets and views
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end
