# PLT Redex helper functions

This repository contains some helper functions for [PLT Redex](https://redex.racket-lang.org/).

Included functionality:
* `clj-base.rkt`: base language. This language is purely functional, with operations based on lambda calculus, and with a syntax similar to Clojure.
* `set.rkt`: functionality related to sets.
* `map.rkt`: functionality related to mappings.

## How to use
It's probably easiest to just copy the functions (or files) you need.

You'll probably be working with a different language, which means you'll need to replace `Lb` with the name of your language. For the rest, `map.rkt` and `set.rkt` do not make any particular assumptions of your language.

## How to contribute

Feel free to submit Pull Requests that add new functionality.

Ideas:
- [ ] Base language with Scheme syntax.
- [ ] Fix TODOs, FIXMEs, and XXXs indicated in the source code.

## License

Distributed under the MIT License.
