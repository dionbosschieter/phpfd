# PHPFD

PHP Filesystem function call detector

Little tool I wrote to check if there are any php files
using the PHP's filesystem functions instead of a custom Storage class.

## Usage:
`$ ./phpfd.phar find --help`
```
Usage:
  find [options]

Options:
  -p, --path=PATH        [default: "/Users/dionbosschieter/Code/PHPFD"]
  -h, --help            Display this help message
  -q, --quiet           Do not output any message
  -V, --version         Display this application version
      --ansi            Force ANSI output
      --no-ansi         Disable ANSI output
  -n, --no-interaction  Do not ask any interactive question
  -v|vv|vvv, --verbose  Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug

Help:
 Searches php files in a given path (current path by default)
```
