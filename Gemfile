git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }
source 'https://rubygems.org'

ruby "~> #{File.read(File.join(__dir__, '.ruby-version')).strip}"

gem 'aws-sdk-s3', '~> 1.30'
gem 'dotenv'
gem 'hashie'
gem 'rexml', '>= 3.3.9'
gem 'ruby-saml', '>= 1.9.0'
gem 'rack-test', '>= 2.0.0'
gem 'rake'
gem 'sinatra', '>= 3.0.4'
gem 'test-unit'
gem 'activesupport'
gem 'puma'

group :development do
  gem 'pry'
end

group :test do
  gem 'simplecov', require: false
  gem 'webmock'
end

group :development, :test do
  gem 'rspec'
end
