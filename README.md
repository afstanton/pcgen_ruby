## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add pcgen_ruby

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install pcgen_ruby

## Usage

This ruby gem is intended to allow reading and writing of PCGen files in Ruby. This should include characters, monsters, items, and rules.

This git repository includes the pcgen repositories from PCGen and BahamutDragon as git submodules in the externals directory. They are included under their own respective licenses for development purposes only, and are used as test fixtures to validate the code. Their presence here does not place their code or data under the MIT license, and will be removed if necessary.

## Development

The spec/fixtures directory contains symlinks to the data directories from the above submodules. As such, if you want to develop in this repo, you will need to run `git submodule update --init` after cloning this.

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/pcgen_ruby.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
