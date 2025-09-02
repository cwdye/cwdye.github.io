# frozen_string_literal: true

source "https://rubygems.org"

#gem 'wdm', '~> 0.1.1', :install_if => Gem.win_platform?

gem "csv", "~> 3.2"

gem 'webrick'

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '>= 1', '< 3'
  gem 'tzinfo-data'
end

group :jekyll_plugins do
  gem 'github-pages'
  gem 'jekyll-octicons'
end
gem "base64", "~> 0.3.0"

gem "bigdecimal", "~> 3.1"

gem "strscan", "~> 3.1"
