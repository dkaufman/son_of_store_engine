source 'https://rubygems.org'

gem 'resque'
gem 'resque_mailer'
gem 'rails', '3.2.3'
gem 'jquery-rails'
gem 'slim'
gem 'twitter-bootstrap-rails'
gem 'bcrypt-ruby'
gem 'redis-store', "~> 1.0.0"
gem 'fabrication'
gem 'faker'
gem 'kaminari'
gem 'newrelic_rpm'

group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'guard'
  gem 'guard-rspec'
  gem 'simplecov'
  gem 'growl'
  gem 'reek', :git => "git://github.com/mvz/reek.git", :branch =>
  "ripper_ruby_parser-2"
  gem 'cane', :git => "git://github.com/square/cane.git"
  gem 'sqlite3'
  gem 'annotate'
  gem 'newrelic_rpm'
end
