source ENV['GEM_SOURCE'] || 'https://rubygems.org'

group :development, :test do
  gem 'puppetlabs_spec_helper',  :require => false
  gem 'puppet-lint', '~> 0.3.2', :require => false
  gem 'rake', '~> 10.1.1',       :require => false
  gem 'rspec', '< 2.99',         :require => false
  gem 'rspec-puppet',            :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby
