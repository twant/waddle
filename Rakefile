require "./app"
require "sinatra/activerecord/rake"

begin 
    require 'minitest/autorun'
rescue LoadError => e
    raise e unless ENV['RAILS_ENV']=="production"
end