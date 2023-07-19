# Ruby version determination

Determine the Ruby versions for your testing matrix based on the gemspec.

Maintaining your CI is tedious and your gem can already specify the compatible Ruby versions using [required_ruby_version](https://guides.rubygems.org/specification-reference/#required_ruby_version).
This action reads your gemspec and provides an output of compatible Ruby versions.

## Supported Ruby versions

A static list of compatible versions is maintained.
This is a subset of [setup-ruby's supported versions](https://github.com/ruby/setup-ruby#supported-versions).

* 3.2
* 3.1
* 3.0
* 2.7
* 2.6
* 2.5
* 2.4
