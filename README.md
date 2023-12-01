# SSH Key Switcher

Simple and efficient Ruby gem for managing and switching between OpenSSH keys seamlessly.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ssh_key_switcher'

```

And then execute:

```bash
$ bundle install

```

Or install it yourself as:

```bash
$ gem install ssh_key_switcher

```

## Usage

### Show Version

```bash
$ ssh_key_switcher version [-v --version]

```

Displays the current version of SSH Key Switcher.

### Ping Servers

```bash
$ ssh_key_switcher ping [-p --ping]

```

Tests the connection to servers listed in **`SshKeySwitcher::Contains::SERVER_NAMES`**.

### Select SSH Key

```bash
$ ssh_key_switcher select [-s --select]

```

Allows you to interactively select and set an OpenSSH key for your sessions.

### List Active SSH Keys

```bash
$ ssh_key_switcher current [-c --current]

```

Displays a list of currently active SSH keys.

### Remove SSH Key

```bash
$ ssh_key_switcher remove [-r --remove]

```

Interactive prompt to remove an OpenSSH key from the list of managed keys.

## Contributing

Bug reports and pull requests are welcome on GitHub at [SSH Key Switcher](https://github.com/minhtang1/ssh_key_switcher).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).
