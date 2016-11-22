# hncr-cli

A Hacker News command line client

## Installation

Get the binary over at [releases](https://github.com/Gangwolf/hncr-cli/releases).

## Usage

###### NOTE: 
The client returns items concurrently, this means
items may not return in order. Its first response, first serve.

```shell
# Print eight items from the 'new' category
$ ./hncr-cli -i new -c 8
```

#### Options
 * `-i TYPE`, `--item=TYPE` The type of item (default: best).
 * `-c NUMBER`, `--count=NUMBER` The number of stories (default: 5).
 * `-h`, `--help` Show help.
 * `-v`, `--version` Print the version and exit.

## Contributing

1. Fork it (https://github.com/Gangwolf/hncr-cli/fork)
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [Dan](https://github.com/Gangwolf) - creator, maintainer