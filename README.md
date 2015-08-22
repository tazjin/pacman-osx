Pacman on OS X
==============

My current work computer is a MacBook for `:reasons:`. As I have only used
Arch for a couple of years and OS X lacks decent package management (no,
Homebrew is not a package manager) the way to go was obviously to run Arch's
[pacman][] on OS X.

Thanks to some work done by [kladd][] I got it up and running very easily.

The aim for this repository is to provide a lot of PKGBUILDs for different
things and eventually an easier way to bootstrap pacman on OS X. (It should
be possible to simply use a default OS X application installer).

## Current packages

Packages that currently have packaging and work on OS X:

* autoconf
* automake
* bash
* cmake
* gettext
* gmp
* gnupg
* gzip
* libarchive
* libassuan
* libgcrypt
* libgpg-error
* libksba
* libtasn1
* libtool
* npth
* osx
* pacman
* pass
* pinentry
* pkg-config
* pwgen
* texinfo
* tree
* xz

## Repository

I intend to put up a simple repository with the packages I built, mostly
for myself. Information about that will be added here once it exists and
it can be used by other people at that point, though I will guarantee
nothing.

[pacman]: https://www.archlinux.org/pacman/
[kladd]: https://github.com/kladd/pacman-osx
