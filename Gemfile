source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.15'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'figaro', '~>1.1.1'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'rspec-rails', '~>3.5.1'
  gem 'factory_girl_rails', '~>4.7.0'
  gem 'capybara', '~>2.7.1'
  gem 'pry-byebug', '~>3.4.0'
  # gem 'guard-rspec', require: false
  gem 'listen', '~> 3.0.7'
  # gem 'guard-rspec', '~> 4.5.2', require: false
  gem 'guard-rspec'
  #移除js测试框架,加快测试速度
  # gem 'guard-jasmine', '~>2.0.6'
  # gem 'jasmine', '~>2.4.0'
  # gem 'jasmine-jquery-rails', '~>2.0.3'
  gem 'guard-livereload', '~>2.5.2'
  # gem 'rack-livereload', '~>0.3.16'
  # gem 'capybara-webkit'
  gem 'parallel_tests'
  gem 'puffing-billy'
  gem 'selenium-webdriver' # used by JavaScript-dependent feature specs (`js: true`)

end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  gem 'capistrano', '~> 3.5.0'
  gem 'capistrano-bundler', '~>1.1.4'
  gem 'capistrano-rails', '~>1.1.7'
  gem 'capistrano-rbenv', '~>2.0.4'
  gem 'capistrano-rvm', '~>0.1.2'
  gem 'capistrano3-nginx', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "guard-zeus"
  gem "rb-inotify", require: false
  gem "rb-fsevent", require: false
  gem "rb-fchange", require: false
end
group :test do
  gem 'email_spec', '~>2.1.0'
  # gem 'email_spec', '~>1.6.0'
end
