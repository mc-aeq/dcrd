sampleconfig
============

[![Build Status](http://img.shields.io/travis/decred/aeqd.svg)](https://travis-ci.org/decred/aeqd)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](http://copyfree.org)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/mc-aeq/aeqd/sampleconfig)

Package sampleconfig provides a single constant that contains the contents of
the sample configuration file for aeqd.  This is provided for tools that perform
automatic configuration and would like to ensure the generated configuration
file not only includes the specifically configured values, but also provides
samples of other configuration options.

## Installation and Updating

```bash
$ go get -u github.com/mc-aeq/aeqd/sampleconfig
```

## License

Package sampleconfig is licensed under the [copyfree](http://copyfree.org) ISC
License.
