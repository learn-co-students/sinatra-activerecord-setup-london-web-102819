# A sample Gemfile
source "https://rubygems.org"

gem 'sinatra'
gem 'thin'
gem 'require_all'
#add these gems to allow usage of ActiveRecord
gem "activerecord", "5.2"
gem "sinatra-activerecord"
gem "rake"

group :development do
	gem 'shotgun'
	gem 'pry'
	#add these gems to be our database adapter gem
	#allows Ruby application to communicate with a SQK database.
	gem "sqlite3", "~>1.3.6" #version to be determined depends on
	#gives us an interactive console that pre-loads database and ActiveRecord relationships for us
	gem "tux"
end