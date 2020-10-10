source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem 'rails', '~> 6.0.1'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.3'

gem 'bootsnap', '>= 1.4.2', require: false

gem 'devise'
gem 'route_translator'

gem 'bootstrap'
gem 'font-awesome-sass'
gem 'jquery-rails'
gem 'sass-rails', '>= 6'

gem 'cpf_cnpj'

gem 'tod'

gem 'smarter_csv', '~> 1.2', require: false
gem 'sentry-raven', '~> 3.0'

gem 'newrelic_rpm'

group :development, :test do
  gem 'byebug'
  gem 'pry-rails'

  gem 'brakeman', require: false
  gem 'bullet'
  gem 'fasterer', require: false
  gem 'flay', require: false
  gem 'rails_best_practices', require: false
  gem 'reek', require: false
  gem 'rspec'
  gem 'rspec-rails'
  gem 'factory_bot_rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'web-console', '>= 3.3.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  gem 'guard', require: false
  gem 'derailed_benchmarks'
  gem 'stackprof'
end
