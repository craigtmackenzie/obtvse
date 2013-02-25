source 'https://rubygems.org'

gem 'rails', '~> 3'

# Extention libraries
gem 'thin', '~> 1'

# Rendering engines and vendor libraries
gem 'jquery-rails', '~> 2'
gem 'redcarpet'

# Misc libraries
gem 'stringex', '~> 1', git: 'git://github.com/rsl/stringex.git'
gem 'kaminari', '~> 0.13'

group :production do
  gem 'pg', '~> 0.13'
end

group :development do
  gem 'rails_best_practices', '~> 1'
end

group :test do
  gem 'capybara', '~> 1'
  gem 'spork', '~> 0.9'
  gem 'database_cleaner', '~> 0.7'
end

group :development, :test do
  gem 'foreman', '~> 0.40'
  gem 'sqlite3', '~> 1', platform: [:ruby, :mswin, :mingw]
  gem 'faker', '~> 1'
  gem 'factory_girl_rails', '~> 1'
end

group :assets do
  gem 'sass-rails', '~> 3'
  gem 'coffee-rails', '~> 3'
  gem 'uglifier', '~> 1'
end
