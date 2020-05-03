# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'cocoapods'
gem 'cocoapods-keys'

gem 'fui', '~> 0.3.0'
gem 'xcpretty'
gem 'second_curtain', '~> 0.2.3'
gem 'fastlane'


plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
