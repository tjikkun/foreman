source 'http://rubygems.org'

gem 'rails', '3.0.10'
gem "jquery-rails"
gem 'json'
gem 'rest-client', :require => 'rest_client'
gem "acts_as_audited", "2.0.0"
gem "has_many_polymorphs", :git => "https://github.com/jystewart/has_many_polymorphs.git", :ref => '03429a61e511f394e9f96af0c8998268ca99d42b'
gem "will_paginate", "~> 3.0.2"
gem "ancestry", "~> 1.2.4"
gem 'scoped_search', '>= 2.3.6'
gem "puppet"
gem 'net-ldap'
gem "safemode", "~> 1.0.1"

group :virt do
  gem "virt", ">= 0.2.1"
  gem "rbovirt", ">= 0.0.9"
  gem "rbvmomi"
  gem "fog", :git => "git://github.com/fog/fog.git"
  #gem "fog", ">= 1.3.2"
end

# database groups, you would most likely need to use only one of these
# to disable the ones you don't want, simple run bundle install --without sqlite mysql mysql2 ...
group :sqlite do
  gem 'sqlite3'
end

group :mysql do
  gem 'mysql'
end

group :mysql2 do
  gem 'mysql2'
end

group :postgresql do
  gem 'pg'
end

group :test do
  gem 'mocha'
  gem 'shoulda'
  gem 'rr'
  gem 'rake'
end

group :development do
  # To use debugger
  gem "ruby-debug", :platforms => :ruby_18
  gem "ruby-debug19", :platforms => :ruby_19
end

group :console do
  gem 'wirb'
  gem 'hirb-unicode'
  gem 'awesome_print', :require => 'ap'
end
