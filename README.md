# fmt - C++ formatting library

This is a [`build2`](https://build2.org/) package repository for [`fmt`](https://fmt.dev/),
a C++ formatting library.

This file contains setup instructions and other details that are more appropriate for development rather than consumption. If you want to use [`fmt`](https://fmt.dev/) in your [`build2`](https://build2.org/)-based project, then instead see the accompanying [`PACKAGE-README.md`](libzydis/PACKAGE-README.md) file.

The development setup for [`fmt`](https://fmt.dev/) uses the standard [`bdep`](https://build2.org/bdep/doc/bdep.xhtml)-based workflow.
For example:

```
git clone .../fmt.git
cd fmt

bdep init -C @gcc cc config.cxx=g++
bdep update
bdep test
```
