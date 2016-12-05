source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.0.1'

gem 'mysql2', '>= 0.3.13', '< 0.5'

gem 'sass'

gem "non-stupid-digest-assets"

gem 'uglifier'

gem 'redcarpet'

gem 'activemodel-serializers-xml'

gem 'rack-cors', :require => 'rack/cors'

gem 'dotenv-rails', '~> 2.1.1'

gem 'bower-rails', '~> 0.10.0'

gem 'devise_token_auth', '~> 0.1.39'

gem "attr_encrypted", "~> 3.0.0"

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Used for 'respond_to' feature
gem 'responders', '~> 2.0'

gem 'stripe'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'puma'

  # Deployment tools
  gem 'capistrano'
  gem 'capistrano-bundler'
  gem 'capistrano-passenger', '>= 0.2.0'
  gem 'capistrano-rails'
  gem 'capistrano-rvm'
  gem 'capistrano-sidekiq'
  gem 'capistrano-git-submodule-strategy', '~> 0.1.22'
end