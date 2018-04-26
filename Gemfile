source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.7'

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :development, :test do
  gem 'pry-rails'
  gem 'faker'
end

group :development do
  gem 'sqlite3'
  gem 'listen'
  gem 'binding_of_caller'
end

group :test do
  gem 'rspec-rails', '~> 3.0'
  gem 'rails-controller-testing'
  gem 'shoulda'
  gem 'factory_girl_rails'
  gem 'simplecov'
end

gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'vuejs'

gem 'yt', '~> 0.13.7'
gem 'bootstrap-sass', '~> 3.3.0.1'
gem 'autoprefixer-rails'
gem 'omniauth-oauth2', '~> 1.1.2'
gem 'jquery-turbolinks'
gem 'youtube_it', github: 'bodrovis/youtube_it'
gem 'figaro'
gem 'nokogiri', '~> 1.8.2'
gem 'rails-html-sanitizer', '~> 1.0.4'
gem 'loofah', '~> 2.2.1'
gem 'rack', '~> 2.0'
