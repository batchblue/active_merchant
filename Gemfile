source 'https://rubygems.org'
gemspec

gem 'jruby-openssl', :platforms => :jruby

group :test, :remote_test do
  # gateway-specific dependencies, keeping these gems out of the gemspec
  # gem 'braintree', '>= 2.0.0'
  gem 'braintree', github: "braintree/braintree_ruby", branch: "raw_apple_pay_preview" # for apple pay support in braintree
  gem 'grizzly_ber', '~> 1.0.3'
end
