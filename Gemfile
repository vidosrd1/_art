source "https://rubygems.org"

gem 'rake', '~> 13.2', '>= 13.2.1'
gem 'rails', '~> 8.0'
gem "propshaft"
gem 'pg'#, '~> 1.5', '>= 1.5.9'
#gem 'sqlite3', '~> 2.3', '>= 2.3.1'
gem 'puma', '~> 6.5'
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "jbuilder"
gem 'bcrypt'#, '~> 3.1', '>= 3.1.20'
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "solid_cache"
gem 'solid_queue', '~> 1.0', '>= 1.0.2'
#gem "solid_queue"
gem "solid_cable"
gem "bootsnap", require: false
gem "kamal", require: false
gem "thruster", require: false
gem "image_processing", "~> 1.2"
gem 'devise', '~> 4.9', '>= 4.9.4'
gem 'madmin', '~> 2.0'
gem 'pagy', '~> 8.6', '>= 8.6.3'
#gem 'pagy', '~> 9.3', '>= 9.3.1'
gem 'cssbundling-rails'#, '~> 1.4', '>= 1.4.1'
gem "appraisal"

gem 'ffaker'#, '~> 2.23'
gem 'friendly_id'#, '~> 5.5', '>= 5.5.1'
gem 'name_of_person'#, '~> 1.1', '>= 1.1.3'
gem 'paper_trail'#, '~> 16.0'
gem 'standardrb'#, '~> 1.0', '>= 1.0.1'
gem 'web-console', group: :development
#, '~> 4.2', '>= 4.2.1'
gem 'standard', '~> 1.42', '>= 1.42.1'

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end
group :development do
  gem 'solargraph'               # run the Solargraph rebuild command in VSC
  #gem "web-console"
end
group :test do
  gem 'activesupport'
  gem 'codecov', require: false
  gem 'i18n'
gem 'minitest', '~> 5.25', '>= 5.25.2'
  #gem 'minitest'
  gem 'minitest-reporters', '~> 1.7', '>= 1.7.1'
  #gem 'minitest-reporters'
  gem 'oj', require: false     # false is for testing with or without it
  gem 'rack'
  gem 'rake-manifest'
  gem 'rematch'
  gem 'rubocop'
  gem 'rubocop-minitest'
  gem 'rubocop-packaging'
  gem 'rubocop-performance'
  gem 'rubocop-rake'
  gem 'simplecov', require: false
  gem "capybara"
  gem "selenium-webdriver"
end
group :apps do
  gem 'rerun'
gem 'sinatra', '~> 4.1', '>= 4.1.1'
  #gem 'sinatra'
  gem 'sinatra-contrib', '~> 4.1'
  #gem 'sinatra-contrib'
  # gem 'slim'
  # gem 'haml'
end
group :performance do
  gem 'benchmark-ips'
  gem 'kalibera'
  gem 'memory_profiler'
end
