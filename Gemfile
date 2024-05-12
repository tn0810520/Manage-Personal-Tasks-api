source "https://rubygems.org"

ruby "3.0.2"

gem "active_model_serializers", "~> 0.10.14"

gem "rack-cors", "~> 2.0", ">= 2.0.2"

gem "jwt", "~> 2.8", ">= 2.8.1"

gem "bcrypt", "~> 3.1", ">= 3.1.12"

gem "faker", "~> 3.2"

gem "dotenv-rails", "~> 2.1", ">= 2.1.1"

gem "devise_token_auth", git: "https://github.com/lynndylanhurley/devise_token_auth"

gem "omniauth", "~> 2.1", ">= 2.1.2"

gem "omniauth-google-oauth2", "~> 1.1", ">= 1.1.1"

gem "byebug", "~> 11.1", ">= 11.1.3"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.3", ">= 7.1.3.2"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", ">= 5.0"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", ">= 4.0.1"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mswin, :mswin64, :mingw, :x64_mingw, :jruby]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin Ajax possible
# gem "rack-cors"

group :development, :test do
  gem "rubocop", "~> 1.26", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "rubocop-rails", "~> 2.14.0", require: false
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: [:mri, :mswin, :mswin64, :mingw, :x64_mingw]
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end