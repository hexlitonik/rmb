# RMB

RMB is a gem helps you generate money in Chinese Yuan.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rmb'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rmb

## Usage

```ruby
RMB.convert('123')            # => '壹佰贰拾叁元'
RMB.convert('12345')          # => '壹万贰仟叁佰肆拾伍元'
RMB.convert('1,234,567,890')  # => '壹拾贰亿叁仟肆佰伍拾陆万柒仟捌佰玖拾元'
```

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

