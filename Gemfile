source 'https://rubygems.org'

gem 'rails', '3.2.5'
gem 'bootstrap-sass', '2.0.0'
gem 'bcrypt-ruby', '3.0.1'
gem 'jquery-rails', '2.0.0'


group :development do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.10.0'
  gem 'guard-rspec', '0.5.5'

  #used to annotate database structure in source code files, rerun after each db:migrate
  gem 'annotate', '~> 2.4.1.beta'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end



group :test do
  gem 'rspec-rails', '2.10.0'
  gem 'capybara', '1.1.2'
  gem 'factory_girl_rails', '1.4.0'

  # System-dependent gems
  gem 'rb-fsevent', '0.9', :require => false
  gem 'growl', '1.0.3'

  gem 'guard-spork', '0.3.2'
  gem 'spork', '0.9.2'

end

group :production do
  gem 'pg', '0.12.2'
end