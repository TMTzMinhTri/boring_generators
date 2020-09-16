# BoringGenerators

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/boring_generators`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'boring_generators'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install boring_generators

## Usage

The boring generator introduces following generators:
- Install Tailwind CSS: `rails generate boring:tailwind:install`
- Install Bootstrap: `rails generate boring:bootstrap:install`
- Install JQuery: `rails generate boring:jquery:install`
- Install FontAwesome via Yarn: `rails generate boring:font_awesome:yarn:install`
- Install FontAwesome via RubyGems: `rails generate boring:font_awesome:ruby_gem:install`
- Install Bullet: `rails generate boring:bullet:install`

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/abhaynikam/boring_generators. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/abhaynikam/boring_generators/blob/master/CODE_OF_CONDUCT.md).


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the BoringGenerators project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/abhaynikam/boring_generators/blob/master/CODE_OF_CONDUCT.md).
