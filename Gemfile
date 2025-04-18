source "https://rubygems.org"
ruby "3.1.4"

# Core Rails
gem "rails", "~> 7.1.5", ">= 7.1.5.1"

# Database
gem "sqlite3", "~> 1.4"

# Web server
gem "puma", "~> 6.0"

# Frontend
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "sprockets-rails"

# bootstrap additions

gem 'bootstrap', '~> 5.3.3'
gem 'sassc-rails'
gem 'jquery-rails'
# Add to your Gemfile
gem 'cssbundling-rails'

gem 'sassc-rails'

# API
gem "jbuilder"

# Internationalization
gem "tzinfo-data", platforms: %i[windows jruby]

# Performance
gem "bootsnap", ">= 1.4.4", require: false

# Development group
group :development, :test do
  gem "debug", "~> 1.8", platforms: %i[mri windows]
  gem "byebug" # Optional for debugging
end

group :development do
  gem "web-console", "~> 4.2"
  gem "error_highlight", "~> 0.5", platforms: [:ruby]
  gem "annotate" # Optional for model annotations
end

group :test do
  gem "capybara", "~> 3.39"
  gem "selenium-webdriver", "~> 4.31"
  gem "webdrivers", "~> 5.2"
end

# Production group (uncomment when deploying)
# group :production do
#   gem "pg", "~> 1.5"
#   gem "redis", "~> 5.0"
# end