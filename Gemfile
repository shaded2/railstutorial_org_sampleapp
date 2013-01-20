source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'bootstrap-sass', '~> 2.2.2.0'
gem 'bcrypt-ruby', '3.0.1'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'
  gem 'guard-spork', '1.2.0'
  gem 'spork', '0.9.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

group :development do
  gem 'annotate', '2.5.0'
end

gem 'jquery-rails', '2.0.2'

group :test do
  gem 'capybara', '1.1.2'
  
  # MacOS specific
  gem 'rb-fsevent', '0.9.1', :require => false
  gem 'growl', :require => false

  # Linux specific
  gem 'rb-inotify', '0.8.8',  :require => false
  gem 'libnotify', '0.5.9', :require => false
end

group :production do
  gem 'pg', '0.12.2'
end