source 'https://rubygems.org'

#generates fake database
gem"ffaker"


# QR code making
gem 'rqrcode'
# AWSOIT lib
gem 'aws-sdk'
gem 'parseconfig'
gem 'mqtt'
gem 'eat'
# gem 'momentjs-rails'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.15'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# Use Haml
# gem 'haml'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jquery-turbolinks'
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

##### birdworks orignal start #####
# Use 'Geocoder' and 'Google maps'
gem 'geocoder'
gem 'gmaps4rails'
# select form that can search
gem "select2-rails"

gem 'therubyracer', platforms: :ruby
# デプロイ
group :deployment do
  gem "capistrano",'~> 3.6.0'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv'
  gem 'capistrano3-unicorn'
  gem 'capistrano-withrsync'
  gem 'capistrano-safe-deploy-to'
  gem 'capistrano-bower'
end
# 管理画面
gem 'activeadmin', '~> 1.0.0.pre4'
gem 'activeadmin-translate'
gem "active_material"
# 認証
gem 'devise'
gem 'devise-i18n'
gem 'cancancan'
gem 'oauth2'

gem 'doorkeeper'
gem 'doorkeeper-jwt'

# テスト
group :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'poltergeist'
  gem 'factory_girl_rails', '~> 4.2.1'
  gem 'database_rewinder'
  gem 'autodoc'
  gem 'json_spec'
end
# RestAPI
gem "grape"
gem "grape-jbuilder"
gem 'grape_logging'
# 画像操作
gem 'carrierwave'
gem 'mini_magick'
gem 'carrierwave-base64'
# WebSocket
source 'https://rubygems.org' do
  gem 'websocket-rails'
  gem 'redis', '3.2.0'            #バグ回避のためバージョン指定
  gem 'faye-websocket', '0.10.0'  #バグ回避のためバージョン指定
end
# 開発環境補助
group :development, :test do
  gem 'pry-rails'  # rails console(もしくは、rails c)でirbの代わりにpryを使われる
  gem 'pry-doc'    # methodを表示
  gem 'pry-byebug' # デバッグを実施(Ruby 2.0以降で動作する)
  gem 'pry-stack_explorer' # スタックをたどれる
end
# ステージング、本番環境用設定
group :staging, :production do
  gem 'unicorn'
end
# 環境設定用
gem 'dotenv-rails'
# チャート
# gem 'chart-js-rails'
gem 'momentjs-rails', '~> 2.11', '>= 2.11.1'
#Charts
gem 'novus-nvd3-rails'
# gem 'chartjs-ror'
# Rails Assets にてフロントエンドの管理
source 'https://rails-assets.org' do
  gem 'rails-assets-requirejs'
  gem 'rails-assets-bootstrap-sass-official', '3.3.6'
  gem 'rails-assets-angular2'
  gem 'rails-assets-angular-bootstrap'
  gem 'rails-assets-angular-resource'
  gem 'rails-assets-angular-websocket', '< 2.0.0'
  gem 'rails-assets-angular-ui-router'
  gem 'rails-assets-angular-animate'
  gem 'rails-assets-angular-aria'
  gem 'rails-assets-angular-material'
  gem 'rails-assets-d3'
end
#ダイアログの拡張
gem 'data-confirm-modal', github: 'ifad/data-confirm-modal'
