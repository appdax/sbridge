source 'https://rubygems.org'

raise 'Ruby 2.2 or newer required' unless RUBY_VERSION >= '2.2.0'

gem 'mongo', '~> 2.2'
gem 'dropbox-sdk', '~> 1.6'
gem 'json', '~> 2.0'

gem 'rake', '~> 11.1', require: false
gem 'whenever', '~> 0.9', require: false

group :development, :test do
  gem 'pry-nav'
  gem 'dotenv'
end

group :test do
  gem 'rspec', '~> 3.4'
  gem 'webmock', '~> 2.0'
  gem 'fakefs', '~> 0.8'
  gem 'hashdiff', '~> 0.3'
  gem 'timecop', '~> 0.8'
  gem 'simplecov'
  gem 'codeclimate-test-reporter'
end
