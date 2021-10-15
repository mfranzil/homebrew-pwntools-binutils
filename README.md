# pwntools binutils scripts

[`pwntools`](https://pwntools.com) depends on `binutils` in order to perform assembly and disassembly of various architectures.

This is a repository of binutils installation scripts for various operating systems, specifically for cross-installations (e.g. assembling VAX on macOS).

Select the directory that corresponds to your operating system, and run `install.sh`.  If you're curious or want to audit our methodology files used by `install.sh` are generated with `generate.sh`.

The macOS installation process uses the [`homebrew`](https://brew.sh) package manager to build binutils from source.

The scripts generated are based on the original [binutils recipe](https://github.com/Homebrew/homebrew-core/blob/master/Formula/binutils.rb) used by `homebrew`.

The binaries are built on your machine, with source fetched directly from the gnu.org server.
