# Sources::Availability::Checker

This Gem houses the Availability Check for the Sources. The Availability Checker is responsible
for scheduling checks on both available and unavailable sources and requesting the checks
to the appropriate operation workers via messaging.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sources-availability-checker'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install sources-availability-checker

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/abellotti/sources-availability-checker.

## License

This gem is available as open source under the terms of the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).