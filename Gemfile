source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.5.3"

gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap-kaminari-views"
gem "bootstrap-sass", "~> 3.4.0"
gem "font-awesome-rails"
gem "jbuilder", "~> 2.5"
gem "jquery-rails", "~> 4.3.3"
gem "mysql2", ">= 0.4.4", "< 0.6.0"
gem "puma", "~> 3.11"
gem "rails", "~> 5.2.2"
gem "rails-i18n", "~> 5.1.3"
gem "sass-rails", "~> 5.0"
gem "turbolinks", "~> 5"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "rspec-rails"
  gem "factory_bot_rails"
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "chromedriver-helper"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "database_cleaner"
  gem "ffaker"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
