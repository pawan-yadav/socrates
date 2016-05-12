source 'http://rubygems.org'
ruby '1.9.3'

# Rails dependencies
gem 'rails', '2.3.18'
gem 'rake', '10.1.0'
gem 'i18n'
gem 'mime-types', '1.25' # To enable update without ruby 2.x


# Database
# gem 'mysql'
gem 'mysql2'
gem 'activerecord-mysql2-adapter'

# Project dependencies
gem 'delayed_job', '2.0.8'
gem 'in_place_editing'
gem 'nokogiri'
gem 'will_paginate', '2.3.16'
gem 'paperclip', '2.7.5'
gem 'wicked_pdf', '1.0.6'
gem 'wkhtmltopdf-binary'
gem 'xss_terminate'
gem 'translator', '1.0.0'
gem 'declarative_authorization'
gem 'searchlogic', '2.5.8'
gem 'calendar_date_select', '1.16.1'
gem 'has_and_belongs_to_many_with_deferred_save', '0.2.0'

# Tests
gem 'test-unit', '1.2.3' # outside group test for enable heroku deployment

group :development, :test do
  gem 'debugger'
  gem 'rspec-rails', '1.3.4'
end

group :test do
  gem 'codeclimate-test-reporter', :require => nil
  gem 'factory_girl'
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'webrat'
  gem 'simplecov', :require => false
  gem 'mocha', '0.12.8'
  gem 'rspec-multi-mock', '0.1.0'
end
