source 'https://rubygems.org'
ruby '2.4.1'

gem 'puma'

gem 'rake'
gem 'hanami',       '1.0.0.rc1'
gem 'hanami-model', '1.0.0.rc1'

gem 'pg'

gem 'slim'
gem 'hanami-bootstrap', '0.4'
gem 'sass'

gem 'sidekiq'
gem 'sidekiq-scheduler'

gem 'redis', '~>3.2'
gem 'hiredis'
gem 'mock_redis'
gem 'connection_pool'

group :development do
  # Code reloading
  # See: http://hanamirb.org/guides/projects/code-reloading
  gem 'shotgun'
end

group :test, :development do
  gem 'dotenv', '~> 2.0'
end

group :test do
  gem 'rspec'
  gem 'rspec-hanami'
  gem 'capybara'
end
