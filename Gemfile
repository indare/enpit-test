# Bower Manager => https://rails-assets.org/
source 'https://rubygems.org'
source 'https://rails-assets.org'

gem 'rails'
gem 'travis'

# Assets
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'rails-assets-bootstrap'
gem 'rails-assets-angular'
gem 'rails-assets-leaflet'

# turbolinks support
gem 'jquery-turbolinks'
gem 'turbolinks'
gem 'jquery-rails'

# Source Map
gem 'coffee-rails-source-maps'
gem 'sass-rails-source-maps'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# CSS Support
gem 'less-rails'

# App Server
gem 'puma'

# Presenter Layer
gem 'draper'

# Haml
gem 'haml-rails'

# Assets log cleaner
gem 'quiet_assets'

# Form Builders
gem 'simple_form'

# # Process Management
gem 'foreman'

# HTML5 Validator
gem 'html5_validators'

# PG/MySQL Log Formatter
gem 'rails-flog'

# Migration Helper
gem 'migrant'

# Pagenation
gem 'kaminari'

# NewRelic
gem 'newrelic_rpm'

# Airbrake
gem 'airbrake'

# HTML Parser
gem 'nokogiri'

# App configuration
gem 'figaro'

# Rack Profiler
gem 'rack-mini-profiler'

# Hash extensions
gem 'hashie'

gem 'mysql2'

group :development do
  # Converter erb => haml
  gem 'erb2haml'
end

group :development, :test do
  # Rails application preloader
  gem 'spring'

  # Railsコンソールの多機能版
  gem 'pry-rails'

  # pryの入力に色付け
  gem 'pry-coolline'

  # デバッカー
  gem 'pry-byebug'

  # Pryでの便利コマンド
  gem 'pry-doc'

  # PryでのSQLの結果を綺麗に表示
  gem 'hirb'
  gem 'hirb-unicode'

  # pryの色付けをしてくれる
  gem 'awesome_print'

  # Rspec
  gem 'rspec-rails'
  gem 'rake_shared_context'

  # fixtureの代わり
  gem "factory_girl_rails"

  # テスト環境のテーブルをきれいにする
  gem 'database_rewinder'

  # Guard
  gem 'guard-rspec'
  gem 'guard-spring'
end

group :production, :staging do
  # ログ保存先変更、静的アセット Heroku 向けに調整
  gem 'rails_12factor'
end
