source 'https://rubygems.org'

group :rake do
  gem 'puppetlabs_spec_helper', '>=1.1.0',  :require => false
  gem 'puppet-blacksmith',                  :require => false
  gem 'rspec-puppet',           '>=2.1.0',  :require => false
  gem 'rake',                   '>=0.9.2.2' :require => false
  gem 'puppet-lint',            '>=1.0.1'   :require => false
end

group :system_tests do
  gem 'beaker-rspec', :require => false
  gem 'beaker',       :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end
