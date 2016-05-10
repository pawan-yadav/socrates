# SocratES : Open Source School Management System

SocratES
 is a is the open source school management system forked from [Project Fedena](https://github.com/projectfedena/fedena) merged with [Fedena LTS](https://github.com/ruby-journal/fedena_lts). It is based on Ruby on Rails and is focused for non-profit entities that want an easy means to manage education records with low budged.

SocratES
 is runs under [Ruby 1.9](https://www.ruby-lang.org/pt/documentation/installation/), [Rails 2.3.18](http://guides.rubyonrails.org/v2.3.11/getting_started.html) and [MySQL Database](http://dev.mysql.com/downloads/).

## What I expect work for future?
  * Ruby 2.x.x or newer support
  * Rails 4.x support
  * Support PostgresSQL, MySQL and MongoDB
  * Responsive layout with Bootstrap 4 or Foundation
  * More Test Coverage
  * An REST API

## License

SocratES
 is released under [MIT License](https://opensource.org/licenses/MIT). Project Fedena is released under the [Apache License 2.0](https://opensource.org/licenses/Apache-2.0).

## Installation
__Warning: This project is not stable yet. You can try to run this app by your own risk!__

__Prerequisite: Knowledge on Ruby on Rails 2.3.18 and Ruby Programing Language__

  1. Instal Ruby and the [Bundler Gem](http://bundler.io/).
  2. Clone this repository: git clone <repo_url>.
  3. Run bundle install at the project folder to install the dependencies.
  4. Configure the database.yml to your database credentials.
  5. Run "rake db:create" to create the database.
  6. Run "rake db:migrate" to generate the databases tables.
  7. Run "rake db:seed" to seed the database with default data.
  8. Run the file "script/server".
  9. Open your browser on http://localhost:3000
  10. Type __admin__ for the username and __admin123__ for the password.
  11. Enjoy the app! :)

## Changes:
 * Bundler support
 * Compatibility with Ruby 1.9.3
 * Kept only support English, Spanish, French and Brazilian Portuguese locales for now
 * Cease support for Ruby 1.8.x
