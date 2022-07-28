source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.4'


gem 'rails', '~> 6.0.5', '>= 6.0.5.1'
gem 'mysql2', '~> 0.5.3'
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'bootstrap-sass', '3.4.1'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'rails-i18n'
gem 'config'
gem "net-imap", require: false
gem "net-pop", require: false
gem "net-smtp", require: false



group :development, :test do
 gem 'pry', '~> 0.14.0'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
 
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'

  gem 'webdrivers'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do 
  gem "rubocop", "~> 1.26", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "rubocop-rails", "~> 2.14.0", require: false
end
