source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# notes on use of annotate gem
# (for full notes see https://github.com/ctran/annotate_models)
# annotate --exclude tests,fixtures,factories
group :development, :test do
  gem 'minitest-rails', git: 'https://github.com/blowmage/minitest-rails.git'
  gem 'minitest'
  gem 'ZenTest'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'sextant'
  gem 'meta_request'
  gem 'annotate'

end

# lbelater - Mike Moore video - has help with integration of Capybara 29:22 and
# I have notes too. See https://github.com/blowmage/minitest-rails-capybara

group :test do
  gem "minitest-rails-capybara"
end
