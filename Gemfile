source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.7'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.12'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'bootstrap-sass', '~> 3.4.1'
gem 'jquery-rails'


group :development, :test do
  gem 'guard'
  gem 'guard-livereload'
  gem 'guard-rspec'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'factory_bot_rails'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
end

