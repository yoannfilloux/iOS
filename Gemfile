source 'https://rubygems.org'

gem 'cocoapods', '>= 1.7.0.beta.1'
gem 'cocoapods-acknowledgements', :git => 'https://github.com/CocoaPods/cocoapods-acknowledgements.git'
gem 'fastlane'
gem 'synx'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval(File.read(plugins_path), binding) if File.exist?(plugins_path)
