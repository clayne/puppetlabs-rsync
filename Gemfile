source "https://rubygems.org"

gem 'rspec', '~> 3.1.0'
gem 'puppetlabs_spec_helper'
if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion,  :require => false
else
  gem 'puppet',                 :require => false
end
