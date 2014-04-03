SpreeVariantOptionsSelect
=========================

Separates the Option Types from the Option Values instead of listing the variants.

It also checks if that combination of option values is available or out of stock.



Installation
------------

Add spree_variant_options_select to your Gemfile:

```ruby
gem 'spree_variant_options_select'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_variant_options_select:install
```

Testing
-------

Be sure to bundle your dependencies and then create a dummy test app for the specs to run against.

```shell
bundle
bundle exec rake test_app
bundle exec rspec spec
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_variant_options_select/factories'
```

Copyright (c) 2013 [name of extension creator], released under the New BSD License
