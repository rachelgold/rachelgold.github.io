source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(URI.open('https://pages.github.com/versions.json').read)

gem 'faraday-retry', '~> 2.4'
gem 'github-pages', versions['github-pages']
