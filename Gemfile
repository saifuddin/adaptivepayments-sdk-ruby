source 'https://rubygems.org'

gemspec

gem 'paypal-sdk-core', :git => "https://github.com/saifuddin/sdk-core-ruby"

if File.exist? File.expand_path('../samples/adaptive_payments_samples.gemspec', __FILE__)
  gem 'adaptive_payments_samples', :path => 'samples', :require => false
  group :test do
    gem 'rspec-rails', :require => false
    gem 'capybara', '~> 2.0.3', :require => false
  end
end

group :test do
  gem 'rspec'
end

gem 'nokogiri', '~> 1.5.9', :platform => :mri_18
