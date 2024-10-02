# cch. Command-line chain for cargo

[![EO principles respected here](https://www.elegantobjects.org/badge.svg)](https://www.elegantobjects.org)
[![DevOps By Rultor.com](http://www.rultor.com/b/h1alexbel/cch)](http://www.rultor.com/p/h1alexbel/cch)
[![We recommend IntelliJ IDEA](https://www.elegantobjects.org/intellij-idea.svg)](https://www.jetbrains.com/idea/)

## How to use

First, install it with [Crates]:

```bash
cargo install cch
```

Then, execute:

```bash
cch clean test
```

It will execute both commands: `clean`, `test` with [cargo][Cargo].

## How to contribute?

Make sure that you have [Rust] and [just] installed on your system, then fork
this repository, make changes, send us a [pull request][guidelines]. We will
review your changes and apply them to the `master` branch shortly, provided
they don't violate our quality standards. To avoid frustration, before sending
us your pull request please run full build:

```bash
just full
```

[Crates]: https://crates.io
[Cargo]: https://doc.rust-lang.org/cargo
[Rust]: https://www.rust-lang.org/tools/install
[just]: https://just.systems/man/en/chapter_4.html
[guidelines]: https://www.yegor256.com/2014/04/15/github-guidelines.html
