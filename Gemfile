source 'http://rubygems.org'

gem 'rails', '3.0.7'

gem 'sqlite3'

group :test do
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'capybara-screenshot', '~>0.0.2'
  gem 'rspec'
end

group :development, :test do
  if RUBY_VERSION =~ /^1\.8\.[\d]+$/
    gem 'ruby-debug'
  else
    gem 'ruby-debug19'
  end
end