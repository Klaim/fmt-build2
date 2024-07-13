# fmt - A C++ library

The `fmt` C++ library provides a fast and safe alternative to C stdio and C++ iostreams.

## Usage

To start using `fmt` in your project, add the following [`depends`](https://build2.org/bpkg/doc/build2-package-manager-manual.xhtml#manifest-package-depends) value to your [`manifest`](https://build2.org/bpkg/doc/build2-package-manager-manual.xhtml#manifests), adjusting the version constraint as appropriate:

```
depends: fmt ^11.0.1
```

Then import the library in your `buildfile`:

```
import libs = fmt%lib{fmt}
```

## Configuration variables

This package provides the following configuration variables:

```
[bool] config.fmt.module ?= false
```

### Configuration variables descriptions

* `fmt.module` - Compile and export the `fmt` C++ module.
