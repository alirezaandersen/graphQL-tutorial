source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'bcrypt'
gem 'puma', '~> 3.7'
gem 'rack-cors', require: 'rack/cors'
gem 'rails', '~> 5.2.0'
gem 'sqlite3'
gem 'validate_url'

gem 'graphql'
gem 'graphql-query-resolver'
gem 'search_object'
gem 'search_object_graphql'

group :development, :test do
  gem 'byebug', platforms: %i(mri mingw x64_mingw)
  gem 'factory_bot_rails'
  gem 'graphiql-rails', '1.5.0'
  gem 'rubocop'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end
