source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.5'

gem 'rails',            '6.1.4.6'
gem 'image_processing', '1.9.3'
gem 'mini_magick',      '4.9.5'
gem 'active_storage_validations', '0.8.9'
gem 'bcrypt',           '3.1.13'
gem 'faker',            '2.11.0'
gem 'will_paginate',            '3.3.0'
gem 'bootstrap-will_paginate',  '1.0.0'
gem 'bootstrap-sass',           '3.4.1'
gem 'puma',       '5.6.4'
gem 'sass-rails', '6.0.0'
gem 'webpacker',  '5.4.0'
gem 'turbolinks', '5.2.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.10.0'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '1.7.2', require: false

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '1.4.2'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '11.1.3', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '4.1.0'

  gem 'listen', '3.4.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '2.1.1'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'capybara',                 '3.35.3'
  gem 'selenium-webdriver',       '3.142.7'
  gem 'webdrivers',               '4.6.0'
  gem 'rails-controller-testing', '1.0.5'
  gem 'minitest',                 '5.11.3'
  gem 'minitest-reporters',       '1.3.8'
  gem 'guard',                    '2.16.2'
  gem 'guard-minitest',           '2.4.6'
end

group :production do
  gem 'pg', '1.2.3'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
#gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
