source 'https://rubygems.org'

gem 'fastlane'
gem 'xcpretty-json-formatter'
gem 'danger'
gem 'danger-commit_lint'
gem 'danger-swiftlint'
gem 'danger-xcode_summary'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
