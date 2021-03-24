# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

DECIDIM_VERSION = "0.23.2"

gem "decidim", DECIDIM_VERSION
gem "decidim-consultations", DECIDIM_VERSION

gem "decidim-action_delegator", github: "coopdevs/decidim-module-action_delegator"
gem "decidim-direct_verifications", github: "Platoniq/decidim-verifications-direct_verifications", branch: "devel"

gem "bootsnap", "~> 1.7"

gem "puma", "~> 5.2.2"
gem "uglifier", "~> 4.1"

gem "faker", "~> 2.17"

group :development, :test do
  gem "byebug", "~> 11.1", platform: :mri

  gem "decidim-dev", DECIDIM_VERSION
end

group :development do
  gem "letter_opener_web", "~> 1.4"
  gem "listen", "~> 3.5"
  gem "spring", "~> 2.1"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

group :production do
  gem 'barnes'
  gem 'dalli'
  gem 'fog-aws'
  gem 'lograge'
  gem 'rack-timeout'
  gem 'rails_autoscale_agent'
  gem 'scout_apm'
  gem 'sentry-raven'
  gem 'sidekiq'
end
