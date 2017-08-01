source 'http://rubygems.org'

gem 'rails', '3.1.1'

gem 'haml', '4.0.4'
gem 'json'
gem 'simple_form'

platforms :jruby do
  gem 'jruby-openssl'
  gem 'activerecord-jdbc-adapter'
  gem 'jdbc-mysql'
  # gem 'activerecord-oracle_enhanced-adapter'

  gem 'mondrian-olap', :git => 'git://github.com/rsim/mondrian-olap.git'

  gem 'kirk'
end

group :development, :test do
  gem 'awesome_print', :require => 'ap'
  gem "nifty-generators"
end
