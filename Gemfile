source 'https://rubygems.org'

gem 'rails', '5.1.7'

ruby '2.6.3'

gem "omniauth"
gem 'turbolinks'
gem 'omniauth-github'
gem 'octokit'
gem 'sass-rails'
gem 'uglifier'
gem 'execjs'
gem 'mini_racer', platforms: :ruby
gem 'bootstrap-sass'
gem 'haml', '4.1.0.beta.1' # LOCKED DOWN 3/27/2019
gem 'html2haml'
gem 'haml-rails'
gem 'jquery-rails'
gem 'overcommit'
gem 'simple_form'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'

# APP-specific gems
gem 'rest-client'
gem 'hassle3'
gem 'kgio'
gem 'tzinfo'
gem 'unicorn'
gem 'backports'
gem 'memcachier'
gem 'dalli'
gem 'yt'

# For old-style action_caching
gem 'actionpack-action_caching'

# Gems from  http://rubysource.com/boosting-your-rails-development-workflow
group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'awesome_print'
  gem 'dawnscanner', require: false
  gem 'rubycritic', require: false

  # For Guard
  gem 'guard'
  gem 'guard-livereload'
  gem 'rack-livereload'
  gem 'ruby_gntp' # Linux
  gem 'rb-fsevent', require: false # for Linux
  gem 'rb-inotify', require: false # for OS X
  # gem 'rb-fchange', require: false # for Windows
end

group :development, :test do
  gem 'sqlite3', '1.3.13' # 2/7/2019: LOCKED DOWN

  # TESTING/ANALYSIS
  gem 'rspec-rails', '4.0.0.beta2' # 4/26/2019: LOCKED DOWN
  gem 'rails-footnotes'
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'email_spec'
  gem 'cucumber'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'

  gem 'factory_bot_rails'
  gem 'launchy'
  gem 'letter_opener'
  gem 'zonebie'

  gem 'rails4_upgrade'

  gem 'travis'

  gem 'simplecov', require: false
  gem 'simplecov-json', require: false

  # This loads environment variables from rails_root/.env if that file exists.
  gem 'dotenv-rails'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
