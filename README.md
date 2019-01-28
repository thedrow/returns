# dry-monads

[![wemake.services](https://img.shields.io/badge/%20-wemake.services-green.svg?label=%20&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAABGdBTUEAALGPC%2FxhBQAAAAFzUkdCAK7OHOkAAAAbUExURQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP%2F%2F%2F5TvxDIAAAAIdFJOUwAjRA8xXANAL%2Bv0SAAAADNJREFUGNNjYCAIOJjRBdBFWMkVQeGzcHAwksJnAPPZGOGAASzPzAEHEGVsLExQwE7YswCb7AFZSF3bbAAAAABJRU5ErkJggg%3D%3D)](https://wemake.services) [![Build Status](https://travis-ci.org/sobolevn/dry_monads.svg?branch=master)](https://travis-ci.org/sobolevn/dry_monads) [![Coverage Status](https://coveralls.io/repos/github/sobolevn/dry_monads/badge.svg?branch=master)](https://coveralls.io/github/sobolevn/dry_monads?branch=master) [![Documentation Status](https://readthedocs.org/projects/dry-monads/badge/?version=latest)](https://dry-monads.readthedocs.io/en/latest/?badge=latest)


Monads for `python` made simple and safe.


## Features

- Provides primitives to write declarative business logic
- Fully typed with annotations and checked with `mypy`,
  allowing you to write type-safe code as well
- No operator overloading or other unpythonic stuff that makes your eyes bleed


## What's inside?

We have several the most iconic monads inside:

- [`Result`, `Failure`, and `Success`](https://dry-monads.readthedocs.io/en/latest/pages/either.html) (also known as `Either`, `Left`, and `Right`)
- `Maybe`, `Some`, and `Nothing` (currently WIP)
- `Just` (currently WIP)

We also care about code readability and developer experience,
so we have included some useful features to make your life easier:

- [Do notation](https://dry-monads.readthedocs.io/en/latest/pages/do-notation.html)


## Inspirations

This module is heavily based on:

- [dry-rb/dry-monads](https://github.com/dry-rb/dry-monads)
- [Ø](https://github.com/dbrattli/OSlash)
- [pymonad](https://bitbucket.org/jason_delaat/pymonad)