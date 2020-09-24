# personnummer [![Build Status](https://secure.travis-ci.org/personnummer/ruby.svg?branch=master)](http://travis-ci.org/personnummer/ruby)

Validate personal identity numbers.

## Installation

Add this to your `Gemfile`

```
gem 'personnummer', :git => 'https://github.com/personnummer/ruby.git'
```

Then run `bundle install`

## Example

```ruby
require 'personnummer'

puts Personnummer.valid?("8507099805")
# => True
```

See [test/test_personnummer.rb](test/test_personnummer.rb) for more examples.

## License

MIT
