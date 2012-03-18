source 'http://ruby.taobao.org/'

gem 'rails', '3.2.2'
gem 'rails-i18n', '0.1.8'
gem 'jquery-rails', '2.0.1'
gem 'rails_autolink', '>= 1.0.6'

# Gems for Mongodb support
gem 'mongoid', '2.4.3'
gem 'bson', '1.5.2'
gem 'bson_ext', '1.5.2'
gem 'mongo-rails-instrumentation', '0.2.4'
gem 'mongoid_auto_increment_id', '0.4.0'
gem 'mongoid_rails_migrations', '~> 0.0.14'

# Word segmentation and search
gem 'chinese_pinyin', '0.4.1'
gem 'rmmseg-cpp-huacnlee', '0.2.9'
gem 'redis-search', '0.7.0'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  # See https://github.com/sstephenson/execjs
  # readme for more supported runtimes
  # gem 'therubyracer'
  gem 'uglifier', '>= 1.0.3'
end

# Upload plugins
gem 'carrierwave', '0.5.8'
gem 'carrierwave-mongoid', '0.1.3', :require => 'carrierwave/mongoid'
gem 'carrierwave-upyun', '0.1.5'
gem 'mini_magick', '3.4'

# User, permission, and third-party authentifcation
gem 'devise', '2.0.4'
gem 'devise_invitable', '1.0.0'
gem 'cancan', '~> 1.6.7'
gem 'omniauth', '~> 1.0.3'
gem 'omniauth-openid', '~> 1.0.1'
gem 'omniauth-douban', :git => "git://github.com/ballantyne/omniauth-douban.git"

# Pagination
gem 'will_paginate', '3.0.3'
gem 'will_paginate_mongoid', '1.0.4'
gem 'bootstrap-will_paginate', '0.0.6'

# Markdown plugins
gem 'redcarpet', '~> 2.1.1'
gem 'hpricot', '~> 0.8.6'
gem 'pygments.rb', '~> 0.2.7'

# Redis, redis namespace and objects
gem 'redis', '2.2.2'
gem 'redis-namespace', '~> 1.0.2'
gem 'redis-objects', '0.5.2'

# YAML configuration
gem 'settingslogic', '~> 2.0.8'

# View components and helpers
gem 'cells', '3.8.3'
gem 'sprite-factory', '1.4.2'
gem 'social-share-button', '0.0.3'
gem 'simple_form', '~> 2.0.1'
gem 'twitter-bootstrap-rails', '~> 2.0.4'
gem 'htmldiff', :git => 'git://github.com/huacnlee/htmldiff.git'
gem 'voteable_mongo_huacnlee', '~> 0.9.2'

# Delayed or Crontab jobs
gem 'whenever', '0.7.3'
gem 'resque', '1.20.0', :require => 'resque/server'
gem 'resque_mailer', '2.0.3'
gem 'juggernaut', '~> 2.1.1'

# Documents, charts and reports
gem 'googlecharts', '~> 1.6.8'
gem 'ekuseru', '~> 0.3.10'
gem 'fastercsv', '~> 1.5.4'

# Gems for Google Maps
gem 'gmaps4rails', '~> 1.4.8'
gem 'mongoid_geo', '~> 0.6.0'

# AWS simple email server
gem 'aws-ses', '~> 0.4.4'
gem 'mail_view', :git => 'git://github.com/37signals/mail_view.git'

# Quick API
gem 'grape', :git => 'git://github.com/intridea/grape.git', :branch => 'frontier'

# Other plugins
gem 'daemon-spawn', '~> 0.4.2'
gem 'quiet_assets', :git => 'git://github.com/AgilionApps/quiet_assets.git'
gem 'tagged-cache', '1.1.1'

group :development, :test do
  gem 'capistrano', '2.11.2'
  gem 'chunky_png', "1.2.5"
  gem "memcache-client", "1.8.5"
  gem 'progress_bar'
  gem 'rspec-rails', '~> 2.8.1'
  gem 'factory_girl_rails', '~> 1.7.0'
  gem 'thin', '~> 1.3.1'
  gem "simplecov", :require => false
  gem "rspec-cells"
  gem "capybara"
end

group :production do
  gem "unicorn", '~> 4.2.0'
  gem 'dalli', '1.1.5'
end
