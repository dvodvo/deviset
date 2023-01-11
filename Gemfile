source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem 'rails', '~> 7.0', '>= 7.0.4'
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem 'turbo-rails', '~> 1.3', '>= 1.3.2'
gem "stimulus-rails"
# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"
# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem "bootsnap", require: false

# user auth access control
gem 'pundit', '~> 2.2'
gem 'devise', '~> 4.8', '>= 4.8.1'
gem 'devise_masquerade', '~> 2.0', '>= 2.0.3'
gem 'administrate', '~> 0.18.0'

# utilities
gem 'geocoder', '~> 1.8', '>= 1.8.1'
gem 'loc', '~> 0.1.1'
# gem 'activerecord-postgis-adapter', '~> 8.0', '>= 8.0.1'
gem 'rqrcode', '~> 2.1', '>= 2.1.1'
gem 'barby', '~> 0.6.8'
# gem 'semacode-ruby19', '~> 0.7.4'
# gem 'carrierwave', '~> 2.2', '>= 2.2.2'
# gem 'carrierwave-aws', '~> 1.5'
gem 'gon', '~> 6.4'
gem 'whenever', '~> 1.0'
# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem 'image_processing', '~> 1.12', '>= 1.12.2'
gem "image_processing", "~> 1.2"
gem 'email_inquire', '~> 0.11.0'

# UI
gem 'browser', '~> 5.3', '>= 5.3.1'
gem "pagy", "~> 5.10"
# gem 'kaminari', '~> 1.2', '>= 1.2.2'
gem 'mobility', '~> 1.2', '>= 1.2.6'
gem 'friendly_id', '~> 5.4', '>= 5.4.2'
# gem 'client_side_validations', '~> 20.0', '>= 20.0.2'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.8'
gem 'view_component', '~> 2.79'
gem 'clipboard', '~> 1.3', '>= 1.3.6'
gem 'wkhtmltopdf-binary', '~> 0.12.6.5'
gem 'wicked_pdf', '~> 2.1'
# gem 'jsbundling-rails', '~> 1.0', '>= 1.0.3'

# external services
gem 'httparty', '~> 0.20.0'
gem 'stripe', '~> 5.45'
# gem 'honeybadger', '~> 4.11'
gem 'telegram-bot', '~> 0.15.6'

# deployment
gem 'capistrano', '~> 3.17'
gem 'capistrano-rails', '~> 1.6', '>= 1.6.2'
gem 'capistrano-passenger', '~> 0.2.1'
gem 'capistrano-rbenv', '~> 2.2'

gem 'rubycritic', '~> 4.6', '>= 4.6.1'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
#  gem 'standard', '~> 1.7', '>= 1.7.3'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.5'
  gem 'webmock', '~> 3.14'
  gem 'simplecov', '~> 0.21.2'
  gem 'rails_anonymous_controller_testing', '~> 0.0.5'

end
