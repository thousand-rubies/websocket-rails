source "http://rubygems.org"

gemspec

gem "rspec-rails", ">= 2.14.2"
gem "therubyrhino"
gem "therubyracer"
gem "jasmine"
gem "headless"
gem "selenium-webdriver"
gem "coffee-script"
gem "thin"
gem "eventmachine"
gem "faye-websocket"
gem "simplecov"
gem "ruby_gntp"
gem "guard", ">= 2.6.0"
gem "guard-rspec", ">= 4.2.9"
gem "guard-coffeescript", ">= 2.0.0"
gem "rb-fsevent"

platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter', :require => 'jdbc-sqlite3', :require => 'arjdbc'
end
platforms :ruby do
  gem 'sqlite3'
end
