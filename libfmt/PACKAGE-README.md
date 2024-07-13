# libfmt - A C++ library

The `libfmt` C++ library provides a fast and safe alternative to C stdio and C++ iostreams.

## Usage

To start using `libfmt` in your project, add the following [`depends`](https://build2.org/bpkg/doc/build2-package-manager-manual.xhtml#manifest-package-depends) value to your [`manifest`](https://build2.org/bpkg/doc/build2-package-manager-manual.xhtml#manifests), adjusting the version constraint as appropriate:

```
depends: libfmt ^11.0.1
```

Then import the library in your `buildfile`:

```
import libs = libfmt%lib{fmt}
```

## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libfmt.module ?= false
```

### Configuration variables descriptions

* `libfmt.module` - Compile and export the `fmt` C++ module.
