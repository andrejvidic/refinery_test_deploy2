source 'https://rubygems.org'

gem 'rails', '4.2.5'

### BOOTSTRAP
gem 'bootstrap-sass', '~> 3.3.6'
gem 'sass-rails', '>= 3.2'
gem 'sprockets-rails', '~> 3.1.1' # with rails 4 and bootstrap needs to be >=2.1.4

gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.1.0' # Use CoffeeScript for .coffee assets and views
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

gem 'jquery-rails' # Use jquery as the JavaScript library
gem 'turbolinks' # Turbolinks makes following links in your web application faster. 
gem 'jbuilder', '~> 2.0' # Build JSON APIs with ease

### REFINERY CMS
gem 'refinerycms', '~> 3.0', '>= 3.0.2'
# gem 'refinerycms', github: 'refinery/refinerycms', branch: 'master'

# Optionally, specify additional Refinery CMS Extensions here:
gem 'refinerycms-authentication-devise', '~> 1.0.4' # The default authentication adapter
gem 'refinerycms-inquiries', '~> 3.0.0'
gem 'refinerycms-search', github: 'refinery/refinerycms-search', branch: 'master'
gem 'refinerycms-acts-as-indexed', ['~> 3.0', '>= 3.0.0'] # searching inside admin interface
gem "refinerycms-blog", github: "refinery/refinerycms-blog", branch: 'master'
gem 'refinerycms-wymeditor', ['~> 1.0', '>= 1.0.6'] # Refinery's visual editor WYMeditor.
gem 'refinerycms-images', '~> 3.0', '>= 3.0.0'
gem 'refinerycms-copywriting', github: 'unixcharles/refinerycms-copywriting', branch: 'master'
gem 'refinerycms-calendar', github: 'refinery/refinerycms-calendar', branch: 'master'

gem 'google-webfonts'
gem 'owlcarousel-rails'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Use Unicorn as the app server
# gem 'unicorn'

group :doc do
  gem 'sdoc', '~> 0.4.0' # bundle exec rake doc:rails generates the API under doc/api.
end

group :development, :test do
  gem 'byebug'
  gem 'sqlite3' # Use sqlite3 as the database for Active Record
end

group :development do
  gem 'web-console', '~> 2.0' # Access an IRB or use <%= console %> in views
  gem 'spring'  # keeps application running in the background
  gem 'capistrano-rails'
  gem 'capistrano-passenger'
  gem 'highline' # prevents ssh password from being shown in console via capistrano
  gem 'quiet_assets'
end

group :production do
  gem 'pg'
end
