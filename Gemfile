# frozen_string_literal: true

source 'https://rubygems.org'

# Jekyll is a simple, blog aware, static site generator
gem 'jekyll', '~> 4.2', '>= 4.2.1'
# A beautiful, minimal theme for Jekyll
gem 'minima', '~> 2.5', '>= 2.5.1'
# Windows Directory Monitor (WDM) is a library which can be used to monitor directories
gem 'wdm', '~> 0.1.1', platforms: %i[mingw x64_mingw mswin]

group :jekyll_plugins do
  # A Jekyll plugin to generate an Atom feed of your Jekyll posts
  gem 'jekyll-feed', '~> 0.15.1'
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  # TZInfo provides access to time zone data and allows times to be converted
  gem 'tzinfo', '~> 2.0', '>= 2.0.4'
  # TZInfo::Data contains data from the IANA Time Zone database
  gem 'tzinfo-data'
end
