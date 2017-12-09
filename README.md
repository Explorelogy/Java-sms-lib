# Explorelogy JAVA SMS Kit V_1.0

> Short blurb about what your product does.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

One to two paragraph statement about your product and what it does.

## Installation

### Windows:

```sh
RXTXcomm.jar goes in \jre\lib\ext (under java)
```
```sh
rxtxSerial.dll goes in \jre\bin
```

### Linux:

```sh
RXTXcomm.jar goes in /jre/lib/ext (under java)
```
```sh
librxtxSerial.so goes in /jre/lib/[machine type] (i386 for instance)
```

Make sure the user is in group lock or uucp so lockfiles work.


### MAC OS X:

```sh
RXTXcomm.jar goes in  /Library/Java/Extensions
```
```sh
librxtxSerial.jnilib goes in /Library/Java/Extensions
```

Run fixperm.sh thats in the directory.  Fix perms is in the Mac_OS_X
subdirectory.

## API Documentation

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History

* 1.0.0
    * CHANGE: Update docs (module code remains unchanged)


## Meta

Dasun Chinthaka – [@Dasun](https://twitter.com/dasun_cn) – dasun@explorelogy.com

Distributed under the license. See ``LICENSE`` for more information.


## Contributing

1. Fork it (<https://github.com/dasuncn/Explorelogy-JAVA-SMS-Kit>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
