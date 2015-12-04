# cpplint - static code checker for C++

This project continues the work of cpplint, a C++ style checker following [Google's C++ style guide](http://google.github.io/styleguide/cppguide.html). It provides cpplint as a PyPI packages and adds a few features and fixes. It is maintained as a fork of [google/styleguide](https://github.com/google/styleguide) in hopes that it can be merged in the future.

To install cpplint from PyPI, run:

```
$ pip install cpplint
```

Then run it with:

```
$ cpplint [OPTIONS] files
```

For full usage instructions, run:

```
$ cpplint --help
```

## Changes

The modifications in this branch are minor fixes and cosmetic changes:

* more default extensions
* python 3k compatibility
* minor fixes around default file extensions
* continuous integration on travis

Thanks to [tkruse](https://github.com/tkruse) for putting cpplint on PyPI and maintaining the PyPI version for many years!

[![Build Status](https://travis-ci.org/theandrewdavis/cpplint.svg)](https://travis-ci.org/theandrewdavis/cpplint)
