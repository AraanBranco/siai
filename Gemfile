source 'https://rubygems.org'

ruby '2.3.1'

gem 'alert_message'
gem 'bootstrap-wysihtml5-rails'
gem 'bootstrap-wysihtml5-rails-font-awesome'
gem "breadcrumbs_on_rails"
gem 'carrierwave'
gem 'carrierwave-ftp', require: 'carrierwave/storage/sftp'
gem 'cancancan'
gem 'clipboard-rails'
gem 'coffee-rails'
gem 'devise'
gem 'devise-i18n'
gem 'figaro'
gem 'friendly_id', '~> 5.1.0'
gem 'font-awesome-sass'
gem 'htmlcompressor'
gem "ifmsui-rails", git: 'https://github.com/luizpicolo/ifmsui-rails'
gem 'ionicons-rails' ## Será removido no futuro
gem 'jbuilder'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'jquery-turbolinks'
gem 'mini_magick'
gem 'modernizr-rails'
gem 'rails', '5.1.1'
gem 'rails-i18n'
gem 'rails-env'
gem 'rails_admin'
gem 'rails_admin-i18n'
gem 'randumb'
gem 'sass-rails'
gem 'search_cop'
gem 'turbolinks'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'uglifier'
gem 'pg'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'binding_of_caller'
  gem 'capybara'
  gem 'email_spec'
  gem 'database_rewinder'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers', git: 'https://github.com/thoughtbot/shoulda-matchers.git', branch: 'rails-5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'coveralls', require: false
  gem 'rails-controller-testing'
end

group :development do
  gem 'yard'
  gem 'puma', '~> 3.0'
  gem 'annotate'
  gem 'better_errors'
  gem 'listen', '~> 3.0.5'
  gem 'web-console'
  gem 'mina', '0.3.8'
  gem 'rails_best_practices', '~> 1.18', '>= 1.18.1'
  gem 'rb-readline'
  gem 'rename'
  gem "rails-erd"
end

group :staging, :production do
  gem 'passenger'
  gem 'mini_racer'
end

group :production do
  gem 'turnout'
end
