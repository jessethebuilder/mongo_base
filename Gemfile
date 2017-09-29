source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'puma', '~> 3.0'

gem 'rails', '~> 5.1.3'

gem 'mongoid'
gem 'mongoid-slug'

gem 'kaminari-mongoid'
gem 'kaminari-actionview'

gem 'devise'

# gem 'mini_magick'
# gem 'fog'
# gem 'carrierwave-mongoid', :require => 'carrierwave/mongoid'
# gem 'aws-sdk', '~> 2'

gem 'bootstrap-sass'
gem 'backbone-on-rails'
gem 'sass-rails', '~> 5.0'
gem 'jquery-rails'
# gem 'turbolinks'
gem 'uglifier', '>= 1.3.0'

# gem "wysiwyg-rails"

# gem 'prawn'
# gem 'prawn-table'

gem 'jbuilder', '~> 2.5'

gem 'farm_ruby', git: 'https://github.com/jessethebuilder/farm_ruby'
gem 'farm_shed', git: 'https://github.com/jessethebuilder/farm_shed', branch: 'lite'
# gem 'farm_shed', path: '/var/www/my_gems/farm_shed', branch: 'lite'
gem 'farm_devise_views', git: 'https://github.com/jessethebuilder/farm_devise_views'
gem 'farm_scrape', git: 'https://github.com/jessethebuilder/farm_scrape.git'

gem 'mongo_address', git: 'https://github.com/jessethebuilder/mongo_address.git'
# gem 'mongo_address', path: '/var/www/my_gems/mongo_address'

gem 'faker'
group :test, :development do
  gem 'rspec-rails'

  gem 'database_cleaner'
  gem 'timecop'
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'spring'
end

group :test do
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'guard-rspec'
  gem 'selenium-webdriver'
  gem 'shoulda'
  gem 'launchy'
  #gem 'webrat'
  gem 'poltergeist'
  gem 'mongoid-rspec'
  gem 'rails-controller-testing'
end

# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

ruby '2.3.1'
