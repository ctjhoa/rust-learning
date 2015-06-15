# rust-learning

A bunch of links to blog posts, articles, videos, etc for learning Rust. Feel free to submit a pull request if you have some links/resources to add. Also, I try to verify that the articles below have some real content (i.e. aren't 2 paragraph blog posts with little information) to ensure I'm not listing "fluff" pieces. If you have an idea for a better way to organize these links, please let me know.

## Introduction
The main documentation is always the best beginning, so if you haven't read yet, start by reading [Rust docs](http://www.rust-lang.org/). You also have an [ebook version](https://github.com/mkaito/rustdocs_ebook) of the doc.

*Tags meanings*
* [official] Something made by a mozilla worker in a mozilla context
* [old] Concepts are still useful but code could not compile.
* [WIP] Work In Progress

## Table of Contents
- [Books](#books)
- [Videos](#videos)
- [Rust in practice](#rust-in-practice)
- [Courses](#courses)
- [Best Practices/Style Guides](#best-practicesstyle-guides)
- [Cheat sheets](#cheat-sheets)
- [RFCs](#rfcs)
- [Code Organization](#code-organization)
- [Compilation](#compilation)
- [CI / Testing](#ci--testing)
- [Comparison with Other Languages](#comparison-with-other-languages)
- [Applications / Libraries / Tools](#applications--libraries--tools)
- [Language stuff](#language-stuff)
  - [Closures](#closures)
  - [Enums](#enums)
  - [Iterators](#iterators)
  - [Lifetime](#lifetime)
  - [Macros](#macros)
  - [Monads](#monads)
  - [Ownership / Concurrency](#ownership--concurrency)
  - [Strings](#strings)
  - [Syntax extensions](#syntax-extensions)
  - [Traits](#traits)
  - [Unsafe](#unsafe)
- [Locale links](#locale-links)
- [People](#people)
  - [Famous Rustacean Bloggers](#famous-rustacean-bloggers)

## Books
* [official] [The Rust Programming Language book](http://doc.rust-lang.org/nightly/book/)
* [Rust Essentials](https://www.packtpub.com/application-development/rust-essentials) - Ivo Balbaert
* [WIP] [Programming Rust](http://www.amazon.com/Programming-Rust-Jim-Blandy/dp/1491927283/) - [Jim Blandy][]
* [KickStarter] [Rust Programming Concepts Book](https://www.kickstarter.com/projects/1712125778/rust-programming-concepts-book) - Matt Carkci

## Videos
You can watch Rust's meetups at [air.mozilla](https://air.mozilla.org/channels/rust/)
* [official] [Stanford Seminar](https://www.youtube.com/watch?v=O5vzLKg7y-k) - [Aaron Turon][]
* [OReilly's Programming in Rust](https://www.reddit.com/r/rust/comments/2trruh/recording_of_jim_blandys_programming_in_rust/) - [Jim Blandy][]
* [My Python's a little Rust-y](https://www.youtube.com/watch?v=3CwJ0MH-4MA) - [Dan Callahan][]
* [Rustlang Screencasts](https://www.youtube.com/playlist?list=PLTOeCUgrkpMNEHx6j0vCH0cuyAIVZadnc) - J M Archer
* [old] [official] [Intro to the Rust programming language](https://www.youtube.com/watch?v=agzf6ftEsLU) - [Alex Crichton][]

## Rust in practice
* [official] [WIP] [rustbyexample](http://rustbyexample.com/) - [Jorge Aparicio][] and [Steve Klabnik][]
* [rosettacode](https://github.com/Hoverbear/rust-rosetta) - [Andrew Hobden][]
* [Why your first FizzBuzz implementation may not work](http://chrismorgan.info/blog/rust-fizzbuzz.html) - [Chris Morgan][]
* [ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust) - gifnksm

## Courses
* [old] [RustTutorial](https://aml3.github.io/RustTutorial/) - aml3

## Best Practices/Style Guides
* [official] [WIP] [Rust Guidelines](https://github.com/rust-lang/rust-guidelines)
* [Error Handling in Rust](http://blog.burntsushi.net/rust-error-handling/) - [Andrew Gallant][]

## Cheat sheets

* [The Periodic Table of Rust Types](http://cosmic.mearie.org/2014/01/periodic-table-of-rust-types/) - Kang Seonghoon
* [Rust Iterator Cheat Sheet](https://danielkeep.github.io/itercheat_baked.html) - [Daniel Keep][]

## RFCs
See [Rust RFCs](https://github.com/rust-lang/rfcs)

## Code Organization
None

## Compilation
* [Rust on OpenWRT (cross compiling to mips-linux-gnu)](https://github.com/japaric/rust-on-openwrt) - [Jorge Aparicio][]

## CI / Testing
* [Helping Travis catch the rustc train part 1](https://huonw.github.io/blog/2015/04/helping-travis-catch-the-rustc-train/) | [part 2](https://huonw.github.io/blog/2015/05/travis-on-the-train-part-2/) - [Huon Wilson][]
* [Rust, Travis, and Github Pages](http://hoverbear.org/2015/03/07/rust-travis-github-pages/) - [Andrew Hobden][]

## Comparison with Other Languages
* [Rust for Rubyists](http://www.rustforrubyists.com/) - [Steve Klabnik][]
* [old] [Rust for C++ Programmers](http://aminb.gitbooks.io/rust-for-c/content/) - [Nick Cameron][]
* [A Swift guide to Rust](http://faq.sealedabstract.com/rust/) - sealedabstract
* [A Quick Comparison of Nim vs. Rust](https://arthurtw.github.io/2015/01/12/quick-comparison-nim-vs-rust.html) - Arthur Liao
* [Rust's Ownership model for JavaScript developers](http://blog.thoughtram.io/rust/2015/05/11/rusts-ownership-model-for-javascript-developers.html) - [Christoph Burgdorf][]
* [A Rust Contributor Tries Their Hand at Go](http://www.polyglotweekly.com/2015/04/24/thoughts-of-a-rustacean-learning-go.html) - [Manish Goregaokar][]
* [Rust for Python Programmers](http://lucumr.pocoo.org/2015/5/27/rust-for-pythonistas/) - Armin Ronacher

## Applications / Libraries / Tools
See the awesome repo [kud1ing/awesome-rust](https://github.com/kud1ing/awesome-rust)

## Language stuff

### Closures
* [Finding Closure in Rust](https://huonw.github.io/blog/2015/05/finding-closure-in-rust/) - [Huon Wilson][]
* [Defaulting to Thread-Safety: Closures and Concurrency](https://huonw.github.io/blog/2015/05/defaulting-to-thread-safety/) - [Huon Wilson][]

### Enums
* [Virtual Structs Part 1: Where Rust’s Enum Shines](http://smallcultfollowing.com/babysteps/blog/2015/05/05/where-rusts-enum-shines/) - [Niko Matsakis][]

### Iterators
* [A Journey into Iterators](http://hoverbear.org/2015/05/02/a-journey-into-iterators/) - [Andrew Hobden][]

### Lifetime
* [Where Rust Really Shines](https://manishearth.github.io/blog/2015/05/03/where-rust-really-shines/) - [Manish Goregaokar][]

### Macros
* [A Practical Intro to Macros in Rust 1.0](https://danielkeep.github.io/practical-intro-to-macros.html) - [Daniel Keep][]

### Monads
* [Option Type part 1](http://blog.8thlight.com/dave-torre/2015/03/11/the-option-type.html) | [part 2](http://blog.8thlight.com/uku-taht/2015/04/29/using-the-option-type-effectively.html) - 8thlight
* [old] [Option Monads in Rust](http://hoverbear.org/2014/08/12/option-monads-in-rust/) - [Andrew Hobden][]

### Ownership / Concurrency
* [official] [Fearless Concurrency with Rust](http://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html) - [Aaron Turon][]
* [Rust ownership, the hard way](http://chrismorgan.info/blog/rust-ownership-the-hard-way.html) - [Chris Morgan][]
* [An alternative introduction to Rust](http://words.steveklabnik.com/a-new-introduction-to-rust) - [Steve Klabnik][]
* [The Problem With Single-threaded Shared Mutability](https://manishearth.github.io/blog/2015/05/17/the-problem-with-shared-mutability/) - [Manish Goregaokar][]
* [Wrapper Types in Rust: Choosing Your Guarantees](https://manishearth.github.io/blog/2015/05/27/wrapper-types-in-rust-choosing-your-guarantees/) - [Manish Goregaokar][]

### Strings
* [String vs &str in Rust functions part 1](http://hermanradtke.com/2015/05/03/string-vs-str-in-rust-functions.html) | [part 2](http://hermanradtke.com/2015/05/06/creating-a-rust-function-that-accepts-string-or-str.html) - [Herman J. Radtke III][]

### Syntax extensions
* [Syntax extensions and regular expressions for Rust](http://blog.burntsushi.net/rust-regex-syntax-extensions/) - [Andrew Gallant][]
* [How to Write a Rust Syntax Extension](http://brodoyouevencode.com/posts/how-to-write-a-rust-syntax-extension/) - [Gulshan Singh][]

### Traits
* [official] [Abstraction without overhead: traits in Rust](http://blog.rust-lang.org/2015/05/11/traits.html) - [Aaron Turon][]
* [A series on trait objects part 1](https://huonw.github.io/blog/2015/01/peeking-inside-trait-objects) | [part 2](https://huonw.github.io/blog/2015/01/the-sized-trait) | [part 3](https://huonw.github.io/blog/2015/01/object-safety) | [part 4](https://huonw.github.io/blog/2015/05/where-self-meets-sized-revisiting-object-safety/) - [Huon Wilson][]
* [Rust traits for developer friendly libraries](https://benashford.github.io/blog/2015/05/24/rust-traits-for-developer-friendly-libraries/) - [Ben Ashford][]
* [Traits and trait objects](http://xania.org/201506/traits-and-trait-objects) - Matt Godbolt

### Unsafe
* [Unsafe Rust: An Intro and Open Questions](http://cglab.ca/~abeinges/blah/rust-unsafe-intro/) - Alexis Beingessner

## Locale links
* [Brazilian Portuguese](pt_BR.md)
* [French](fr_FR.md)
* [Russian](ru_RU.md)

## People
This is the official [Rust Team](http://www.rust-lang.org/team.html) and [Servo Team](https://github.com/orgs/servo/people)

You search for a rustacean ? [http://www.rustaceans.org/](http://www.rustaceans.org/)

### Famous Rustacean Bloggers
* [Andrew Gallant][] - [blog](http://blog.burntsushi.net/)
* [Andrew Hobden][] - [blog](http://hoverbear.org/tag/rust/)
* [Brian Anderson][] - [blog](https://brson.github.io/blog/index.html)
* [Christoph Burgdorf][] - [blog](https://cburgdorf.wordpress.com/)
* [Chris Morgan][] - [blog](http://chrismorgan.info/blog/tags/rust.html)
* [Felix S Klock II][] - [blog](http://blog.pnkfx.org/)
* [Huon Wilson][] - [blog](https://huonw.github.io/blog/)
* [Manish Goregaokar][] - [blog](https://manishearth.github.io/)
* [Nick Cameron][] - [blog](http://featherweightmusings.blogspot.fr/)
* [Niko Matsakis][] - [blog](http://smallcultfollowing.com/babysteps/)
* [Patrick Walton][] - [blog](https://pcwalton.github.io/)
* [Yehuda Katz][] - [blog](http://yehudakatz.com/)
* [Steve Klabnik][] - [blog](http://words.steveklabnik.com/)

Don't forget [Ferris](http://www.rustacean.net/) the unofficial mascot.

<!-- Rustaceans -->
[Aaron Turon]: https://github.com/aturon
[Alex Crichton]: https://github.com/alexcrichton
[Andrew Gallant]: https://github.com/BurntSushi
[Andrew Hobden]: https://github.com/Hoverbear
[Ben Ashford]: https://github.com/benashford
[Brian Anderson]: https://github.com/brson
[Carl Lerche]: https://github.com/carllerche
[Chris Morgan]: https://github.com/chris-morgan
[Christoph Burgdorf]: https://github.com/cburgdorf
[Daniel Keep]: https://github.com/DanielKeep
[Dan Callahan]: https://github.com/callahad
[Eduard Burtescu]: https://github.com/eddyb
[Felix S Klock II]: https://github.com/pnkfelix
[Gulshan Singh]: https://github.com/gsingh93
[Herman J. Radtke III]: https://github.com/hjr3
[Jakub Bukaj]: https://github.com/jakub-
[Jim Blandy]: https://github.com/jimblandy
[Jorge Aparicio]: https://github.com/japaric
[Josh Matthews]: https://github.com/jdm
[Luqman Aden]: https://github.com/luqmana
[Huon Wilson]: https://github.com/huonw
[Manish Goregaokar]: https://github.com/Manishearth
[Nick Cameron]: https://github.com/nrc
[Niko Matsakis]: https://github.com/nikomatsakis
[Patrick Walton]: https://github.com/pcwalton
[Seo Sanghyeon]: https://github.com/sanxiyn
[Simon Sapin]: https://github.com/SimonSapin
[Steve Klabnik]: https://github.com/steveklabnik
[Steven Fackler]: https://github.com/sfackler
[Tetsuharu OHZEKI]: https://github.com/saneyuki
[Yehuda Katz]: https://github.com/wycats
