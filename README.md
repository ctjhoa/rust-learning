# rust-learning

A bunch of links to blog posts, articles, videos, etc for learning Rust. Feel free to submit a pull request if you have some links/resources to add. Also, I try to verify that the articles below have some real content (i.e. aren't 2 paragraph blog posts with little information) to ensure I'm not listing "fluff" pieces. If you have an idea for a better way to organize these links, please let me know.

## Introduction
The main documentation is always the best beginning, so if you haven't read yet, start by reading [Rust docs](http://www.rust-lang.org/). You also have an [ebook version](https://github.com/mkaito/rustdocs_ebook) of the doc.

*Tags meanings*
* [official] Something made by a mozilla worker in a mozilla context
* [old] Concepts are still useful but code could not compile.

## Table of Contents
- [Books](#books)
- [Videos](#videos)
- [Rust in practice](#rust-in-practice)
- [Courses](#courses)
- [Best Practices/Style Guides](#best-practicesstyle-guides)
- [RFCs](#rfcs)
- [Code Organization](#code-organization)
- [CI / Testing](#ci--testing)
- [Comparison with Other Languages](#comparison-with-other-languages)
- [Applications / Libraries / Tools](#applications--libraries--tools)
- [Language stuff](#language-stuff)
  - [Borrowing / Concurrency](#borrowing--concurrency)
  - [Closures](#closures)
  - [Enums](#enums)
  - [Iterators](#iterators)
  - [Macros](#macros)
  - [Monads](#monads)
- [People](#people)
  - [Rust Core Team](#rust-core-team)
  - [Rust Gurus](#rust-gurus)
  - [Servo Team](#servo-team)

## Books
* [official] [The Rust Programming Language book](http://doc.rust-lang.org/nightly/book/)

## Videos
You can watch Rust's meetups at [air.mozilla](https://air.mozilla.org/channels/rust/)
* [official] [Stanford Seminar](https://www.youtube.com/watch?v=O5vzLKg7y-k) - [Aaron Turon][]
* [OReilly's Programming in Rust](https://www.reddit.com/r/rust/comments/2trruh/recording_of_jim_blandys_programming_in_rust/) - [Jim Blandy][]
* [old] [official] [Intro to the Rust programming language](https://www.youtube.com/watch?v=agzf6ftEsLU) - [Alex Crichton][]

## Rust in practice
* [official] [rustbyexample](http://rustbyexample.com/) - [Jorge Aparicio][] and [Steve Klabnik][]
* [rosettacode](https://github.com/Hoverbear/rust-rosetta) - [Andrew Hobden][]
* [ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust) - gifnksm

## Courses
* [RustTutorial](https://aml3.github.io/RustTutorial/) - aml3

## Best Practices/Style Guides
* [official] [Rust Guidelines](https://github.com/rust-lang/rust-guidelines)

## RFCs
See [Rust RFCs](https://github.com/rust-lang/rfcs)

## Code Organization
None

## CI / Testing
* [Helping Travis catch the rustc train part 1](https://huonw.github.io/blog/2015/04/helping-travis-catch-the-rustc-train/) | [part 2]() - [Huon Wilson][]
* [Rust, Travis, and Github Pages](http://hoverbear.org/2015/03/07/rust-travis-github-pages/) | [Andrew Hobden]()

## Comparison with Other Languages
* [Ruby](http://www.rustforrubyists.com/) - [Steve Klabnik][]
* [C++](http://aminb.gitbooks.io/rust-for-c/content/) - [Nick Cameron][]
* [Swift](http://faq.sealedabstract.com/rust/) - sealedabstract
* [Nim](https://arthurtw.github.io/2015/01/12/quick-comparison-nim-vs-rust.html) - arthurtw

## Applications / Libraries / Tools
See the awesome repo [kud1ing/awesome-rust](https://github.com/kud1ing/awesome-rust)

## Language stuff

### Borrowing / Concurrency
* [official] [Fearless Concurrency with Rust](http://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html) - [Aaron Turon][]
* [An alternative introduction to Rust](http://words.steveklabnik.com/a-new-introduction-to-rust) - [Steve Klabnik][]

### Closures
* [Finding Closure in Rust](https://huonw.github.io/blog/2015/05/finding-closure-in-rust/) - [Huon Wilson][]

### Enums
* [Virtual Structs Part 1: Where Rust’s Enum Shines](http://smallcultfollowing.com/babysteps/blog/2015/05/05/where-rusts-enum-shines/) - [Niko Matsakis][]

### Iterators
* [A Journey into Iterators](http://hoverbear.org/2015/05/02/a-journey-into-iterators/) - [Andrew Hobden][]

### Macros
* [old] [A Quick Intro to Rust Macros](https://danielkeep.github.io/quick-intro-to-macros.html) - [Daniel Keep][]

### Monads
* [Option Type part 1](http://blog.8thlight.com/dave-torre/2015/03/11/the-option-type.html) | [part 2](http://blog.8thlight.com/uku-taht/2015/04/29/using-the-option-type-effectively.html) - 8thlight
* [old] [Option Monads in Rust](http://hoverbear.org/2014/08/12/option-monads-in-rust/) - [Andrew Hobden]()

## People
You search for a rustacean ? [http://www.rustaceans.org/](http://www.rustaceans.org/)

### Rust Core Team \*
* [Aaron Turon][]
* [Alex Crichton][]
* [Brian Anderson][] - [blog](https://brson.github.io/blog/index.html)
* [Huon Wilson][] - [blog](https://huonw.github.io/blog/)
* [Niko Matsakis][] - [blog](http://smallcultfollowing.com/babysteps/)
* [Patrick Walton][] - [blog](https://pcwalton.github.io/)
* [Yehuda Katz][] - [blog](http://yehudakatz.com/)
* [Steve Klabnik][] - [blog](http://words.steveklabnik.com/)

\* *See this [note](https://github.com/rust-lang/rust-wiki-backup/blob/master/Note-core-team.md)*

### Rust Gurus \*
* [Andrew Gallant][] - [blog](http://blog.burntsushi.net/)
* [Carl Lerche][]
* [Chris Morgan][] - [blog](http://chrismorgan.info/blog/tags/rust.html)
* [Eduard Burtescu][]
* [Felix S Klock II][] - [blog](http://blog.pnkfx.org/)
* [Jakub Bukaj][]
* [Jim Blandy][]
* [Jorge Aparicio][]
* [Luqman Aden][]
* [Nick Cameron][] - [blog](http://featherweightmusings.blogspot.fr/)
* [Seo Sanghyeon][]
* [Steven Fackler][]

\* *Rustaceans who work or has worked for Mozilla*

### Servo Team
* [Josh Matthews][]
* [Manish Goregaokar][]
* [Simon Sapin][]
* [Tetsuharu OHZEKI][]

<!-- Rust Core Team -->
[Aaron Turon]: https://github.com/aturon
[Alex Crichton]: https://github.com/alexcrichton
[Brian Anderson]: https://github.com/brson
[Huon Wilson]: https://github.com/huonw
[Niko Matsakis]: https://github.com/nikomatsakis
[Patrick Walton]: https://github.com/pcwalton
[Yehuda Katz]: https://github.com/wycats
[Steve Klabnik]: https://github.com/steveklabnik

<!-- Rust Gurus -->
[Andrew Gallant]: https://github.com/BurntSushi
[Carl Lerche]: https://github.com/carllerche
[Chris Morgan]: https://github.com/chris-morgan
[Eduard Burtescu]: https://github.com/eddyb
[Felix S Klock II]: https://github.com/pnkfelix
[Jakub Bukaj]: https://github.com/jakub-
[Jim Blandy]: https://github.com/jimblandy
[Jorge Aparicio]: https://github.com/japaric
[Luqman Aden]: https://github.com/luqmana
[Nick Cameron]: https://github.com/nrc
[Seo Sanghyeon]: https://github.com/sanxiyn
[Steven Fackler]: https://github.com/sfackler

<!-- Servo Team -->
[Josh Matthews]: https://github.com/jdm
[Manish Goregaokar]: https://github.com/Manishearth
[Tetsuharu OHZEKI]: https://github.com/saneyuki
[Simon Sapin]: https://github.com/SimonSapin

<!-- Others -->
[Daniel Keep]: https://github.com/DanielKeep
[Andrew Hobden]: https://github.com/Hoverbear
[bluss]: https://github.com/bluss
