# icelab-style

Icelab internal shared style configurations.

## Installation

Add this line to your application's Gemfile:

```ruby
group :development do
  gem "icelab-style"
end
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install icelab-style

## Usage

Create a `.rubocop.yml` with the following directives:

```yaml
inherit_gem:
  icelab-style:
    - default.yml
```

There's no need to add the `rubocop` gem to your project's `Gemfile`; `rubocop` is a dependency of `icelab-style`, to ensure we use a consistent minimum version across all of our projects.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Credits

Inspired by [percy-style](https://github.com/percy/percy-style) by [Percy](https://percy.io/).
