source "https://rubygems.org"

gem "fastlane", path: "/Users/felixkrause/Developer/fastlane"
gem "cocoapods", ">= 1.5.3"
gem "pry"

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
