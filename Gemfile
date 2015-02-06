source 'https://rubygems.org'

require 'json'
require 'open-uri'
gem 'guard'
gem 'jekyll'
gem 'guard-livereload'

versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
