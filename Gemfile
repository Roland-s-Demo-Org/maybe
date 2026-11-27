source "https://rubygems.org"

ruby file: ".ruby-version"

# Rails
gem "rails", "~> 8.0.0"

# Drivers
gem "pg", "~> 1.5"

# Deployment
gem "puma", '>= 7.2.2'
gem "bootsnap", require: false

# Assets
gem "importmap-rails"
gem "propshaft"
gem "tailwindcss-rails"
gem "lucide-rails", github: "maybe-finance/lucide-rails"

# Hotwire
gem "stimulus-rails"
gem "turbo-rails"

# Temporary pin to commit to fix crypto.randomUUID() errors.  Revert this when the change has been released.
gem "hotwire_combobox", github: "josefarias/hotwire_combobox", ref: "b827048a8305e1115d5f96931ba1c9750d1e59fc"

# Background Jobs
gem "good_job"

# Error logging
gem "vernier"
gem "rack-mini-profiler"
gem "sentry-ruby"
gem "sentry-rails"
gem "logtail-rails"

# Active Storage
gem "aws-sdk-s3", "~> 1.177.0", require: false
gem "image_processing", '>= 2.0.3'

# Other
gem "bcrypt", '~> 3.1.22'
gem "jwt", '>= 2.10.3'
gem "faraday", '>= 2.14.3'
gem "faraday-retry"
gem "faraday-multipart"
gem "inline_svg"
gem "octokit"
gem "pagy"
gem "rails-settings-cached"
gem "tzinfo-data", platforms: %i[windows jruby]
gem "csv"
gem "redcarpet"
gem "stripe"
gem "intercom-rails"
gem "plaid"
gem "rotp", "~> 6.3"
gem "rqrcode", "~> 2.2"

group :development, :test do
  gem "debug", platforms: %i[mri windows]
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
  gem "i18n-tasks"
  gem "erb_lint"
  gem "dotenv-rails"
end

group :development do
  gem "hotwire-livereload"
  gem "letter_opener"
  gem "ruby-lsp-rails"
  gem "web-console"
  gem "faker"
  gem "benchmark-ips"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "mocha"
  gem "vcr"
  gem "webmock"
  gem "climate_control"
  gem "simplecov", require: false
end

gem "rack-session", ">= 2.1.2"

gem "activestorage", ">= 8.0.5.2"

gem "concurrent-ruby", ">= 1.3.7"

gem "net-imap", ">= 0.5.14"

gem "websocket-driver", ">= 0.9.0"

gem "nokogiri", ">= 1.18.9"

gem "crass", ">= 1.0.7"

gem "msgpack", ">= 1.8.7"

gem "aws-sdk-core", ">= 3.260.0"

gem "activesupport", ">= 8.0.5.2"

gem "json", ">= 2.19.6"

gem "rack", ">= 3.1.21"

gem "uri", ">= 1.0.4"

gem "rubyzip", ">= 3.4.0"

gem "actionpack", ">= 8.0.5.2"

gem "ruby-lsp", ">= 0.26.9"
