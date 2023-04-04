source "http://rubygems.org"

gemspec

gem "rspec-rails", ">= 2.14.1"
gem "therubyrhino"
gem "therubyracer"
gem "jasmine", ">= 2.0.2"
gem "headless"
gem "selenium-webdriver"
gem "coffee-script"
gem "thin"
gem "eventmachine"
gem "faye-websocket", ">= 0.11.0"
gem "simplecov"
gem "ruby_gntp"
gem "guard"
gem "guard-rspec"
gem "guard-coffeescript"
gem "rb-fsevent"

platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter', :require => 'jdbc-sqlite3', :require => 'arjdbc'
end
platforms :ruby do
  gem 'sqlite3'
end
