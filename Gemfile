source "https://rubygems.org"

ruby file: ".ruby-version"

# Rails
gem "rails", "~> 7.2.2"

# Drivers
gem "pg", '~> 1.6.0'

# Deployment
gem "puma", ">= 5.0"
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
gem "bcrypt", '~> 3.1.21'
gem "jwt", '>= 3.1.0'
gem "faraday", '>= 2.12.3'
gem "faraday-retry"
gem "faraday-multipart"
gem "inline_svg"
gem "octokit"
gem "pagy", '>= 43.6.1'
gem "rails-settings-cached"
gem "tzinfo-data", platforms: %i[windows jruby]
gem "csv"
gem "redcarpet"
gem "stripe", '>= 19.5.0'
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

gem "activestorage", ">= 7.2.3.2"

gem "nokogiri", ">= 1.19.4"

gem "websocket-driver", ">= 0.8.2"

gem "msgpack", ">= 1.8.4"

gem "rack", ">= 3.1.21"

gem "json", ">= 2.19.8"

gem "uri", ">= 1.0.4"

gem "mail", ">= 2.9.1"

gem "loofah", ">= 2.25.2"

gem "rails-html-sanitizer", ">= 1.7.1"

gem "psych", ">= 5.4.0"
