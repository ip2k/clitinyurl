# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "clitinyurl"
  gem.add_dependency 'clipboard'
  gem.executables = ['tinyurl']
  gem.homepage = "http://seanp2k.com"
  gem.license = "Creative Commons by-nc-sa"
  gem.summary = "Shortens a URL using the v.gd API (same thing as is.gd)"
  gem.description = "Uses the v.gd API and provides an executable CLI wrapper to shorten URLs directly from your terminal and copies the short URL to your clipboard"
  gem.email = "github@seanp2k.endjunk.com"
  gem.authors = ["ip2k"]
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new

