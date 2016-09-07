# rust-learning [![Build Status](https://travis-ci.org/ctjhoa/rust-learning.svg?branch=master)](https://travis-ci.org/ctjhoa/rust-learning)

A bunch of links to blog posts, articles, videos, etc for learning Rust. Feel free to submit a pull request if you have some links/resources to add. Also, I try to verify that the articles below have some real content (i.e. aren't 2 paragraph blog posts with little information) to ensure I'm not listing "fluff" pieces. If you have an idea for a better way to organize these links, please let me know.

## Introduction

The main documentation is always the best beginning, so if you haven't read yet, start by reading [Rust docs](http://www.rust-lang.org/). You also have an [ebook version](http://killercup.github.io/trpl-ebook/) of the doc.

### Tags meanings

* [official] Something made by a mozilla worker in a mozilla context
* [old] Concepts are still useful but code could not compile.
* [WIP] Work In Progress

## Table of Contents

* [Books](#books)
* [Videos](#videos)
* [Podcasts](#podcasts)
* [Rust in practice](#rust-in-practice)
* [Best Practices/Style Guides](#best-practicesstyle-guides)
* [Cheat sheets](#cheat-sheets)
* [RFCs](#rfcs)
* [Code Organization](#code-organization)
* [Compilation](#compilation)
* [CI / Testing](#ci--testing)
* [Comparison with Other Languages](#comparison-with-other-languages)
* [Applications / Libraries / Tools](#applications--libraries--tools)
* [Language stuff](#language-stuff)
  * [Closures](#closures)
  * [Enums](#enums)
  * [Iterators](#iterators)
  * [Lifetime](#lifetime)
  * [Macros](#macros)
  * [MIR](#mir)
  * [Monads](#monads)
  * [Ownership / Concurrency](#ownership--concurrency)
  * [Strings](#strings)
  * [Syntax extensions](#syntax-extensions)
  * [Traits](#traits)
  * [Unsafe](#unsafe)
* [Locale links](#locale-links)
* [People](#people)
  * [Famous Rustacean Bloggers](#famous-rustacean-bloggers)
* [Tutorials & Workshop Materials](#tutorials-workshop-materials)

## Books

* [official] [The Rust Programming Language](http://doc.rust-lang.org/nightly/book/)
* [official] [The Rustonomicon - The Dark Arts of Advanced and Unsafe Rust Programming](https://doc.rust-lang.org/nightly/nomicon/)
* [Why Rust?](http://www.oreilly.com/programming/free/files/why-rust.pdf) - Jim Blandy
* [Rust-101](https://www.ralfj.de/projects/rust-101/main.html) - Ralf Jung
* [Rust Essentials](https://www.packtpub.com/application-development/rust-essentials) - Ivo Balbaert
* [WIP] [Programming Rust](http://shop.oreilly.com/product/0636920040385.do) - [Jim Blandy][]

## Videos

You can watch Rust's meetups at [air.mozilla](https://air.mozilla.org/channels/rust/)

* [official] [Stanford Seminar](https://www.youtube.com/watch?v=O5vzLKg7y-k) - [Aaron Turon][]
* [official] [The Rust Programming Language](https://www.youtube.com/watch?v=d1uraoHM8Gg) - [Alex Crichton][]
* [official] [RustCamp 2015](http://confreaks.tv/events/rustcamp2015)
* [official] [The History of Rust](https://www.youtube.com/watch?v=79PSagCD_AY) - [Steve Klabnik][]
* [OReilly's Programming in Rust](https://www.reddit.com/r/rust/comments/2trruh/recording_of_jim_blandys_programming_in_rust/) - [Jim Blandy][]
* [My Python's a little Rust-y](https://www.youtube.com/watch?v=3CwJ0MH-4MA) - [Dan Callahan][]
* [What Is Rust?](http://www.infoq.com/presentations/rust-gc) - [Yehuda Katz][]
* [Rustlang Screencasts](https://www.youtube.com/playlist?list=PLTOeCUgrkpMNEHx6j0vCH0cuyAIVZadnc) - J M Archer
* [LambdaConf 2015 - In Rust We Trust](https://www.youtube.com/watch?v=-dxqbhLIgdMhttp://confreaks.tv/events/rustcamp2015) - Alex Burkhart

## Podcasts

* [Rusty radio](http://rustyrad.io/) - Alex Newman
* [New Rustacean](http://www.newrustacean.com) - [Chris Krycho][]

## Rust in practice

* [official] [rustbyexample](http://rustbyexample.com/) - [Jorge Aparicio][] and [Steve Klabnik][]
* [rosettacode](https://github.com/Hoverbear/rust-rosetta) - [Andrew Hobden][]
* [Why your first FizzBuzz implementation may not work](http://chrismorgan.info/blog/rust-fizzbuzz.html) - [Chris Morgan][]
* [An annotation of the Rust standard library](https://github.com/brson/annotated-std-rs) - [Brian Anderson][]
* [ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust) - gifnksm
* [Advent of Code](https://github.com/LD250/adventofcode_rust) - Denys Levchenko
* [ArcadeRS](http://jadpole.github.io/arcaders/arcaders-1-0) - Jessy Pelletier
* [Rust in Detail: Writing Scalable Chat Service from Scratch](https://nbaksalyar.github.io/) - Nikita Baksalyar
* [rustlings: small rust exercises](https://github.com/carols10cents/rustlings) - Carol Nichols
* [Learning Rust With Entirely Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/) - [Alexis Beingessner][]
* [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/?updated=2015-11-08) - Jake Goulding
* [Let's build a browser engine!](http://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html) - Matt Brubeck
* [Understanding Over Guesswork](http://hoverbear.org/2015/09/12/understand-over-guesswork/) - [Andrew Hobden][]
* [Writing an OS in Rust](http://os.phil-opp.com/) - Philipp Oppermann
* [Creating Nintendo 64 emulator from scratch in Rust!](https://www.youtube.com/playlist?list=PL-sXmdrqqYYcznDg4xwAJWQgNL2gRray2) - Jake Taylor
* [The Many Kinds of Code Reuse in Rust](http://cglab.ca/~abeinges/blah/rust-reuse-and-recycle/) - [Alexis Beingessner][]
* [Make a Lisp](https://github.com/kanaka/mal/tree/master/rust) - Joel Martin
* [Modeling Graphs in Rust Using Vector Indices](http://smallcultfollowing.com/babysteps/blog/2015/04/06/modeling-graphs-in-rust-using-vector-indices/) - [Niko Matsakis][]
* [Rust basics and beyond](https://medium.com/learning-rust/rust-basics-e73304ab35c7#.atrb20z9w) | [part 2](https://medium.com/learning-rust/rust-beyond-the-basics-4fc697e3bf4f#.al8ptqjax) - Dumindu

## Best Practices/Style Guides

* [official] [WIP] [Rust Guidelines](https://github.com/rust-lang/rust/tree/master/src/doc/style)
* [Rust Design Patterns](https://github.com/nrc/patterns) - [Nick Cameron][]
* [Error Handling in Rust](http://blog.burntsushi.net/rust-error-handling/) - [Andrew Gallant][]
* [Reading Rust Function Signatures](http://hoverbear.org/2015/07/10/reading-rust-function-signatures/) - [Andrew Hobden][]
* [Good Practices for Writing Rust Libraries](https://pascalhertleif.de/artikel/good-practices-for-writing-rust-libraries/) - Pascal Hertleif
* [Rustic Bits](https://llogiq.github.io/2016/02/11/rustic.html) - [Llogiq][]

## Cheat sheets

* [official] [Syntax Index](https://doc.rust-lang.org/book/syntax-index.html)
* [The Periodic Table of Rust Types](http://cosmic.mearie.org/2014/01/periodic-table-of-rust-types/) - Kang Seonghoon
* [Rust Iterator Cheat Sheet](https://danielkeep.github.io/itercheat_baked.html) - [Daniel Keep][]
* [Rust String Conversions Cheat Sheet](https://docs.google.com/spreadsheets/d/19vSPL6z2d50JlyzwxariaYD6EU2QQUQqIDOGbiGQC7Y/pubhtml?gid=0&single=true) - GavinB

## RFCs

See [Rust RFCs](https://github.com/rust-lang/rfcs)

## Code Organization

None

## Compilation

* [rust-cross, Everything you need to know about cross compiling Rust programs!](https://github.com/japaric/rust-cross) - [Jorge Aparicio][]
* [How to cross compile Rust from OS X to FreeBSD](https://github.com/yohanesu75/crossrust) - yohanesu75
* [Cross Compiling for Raspberry Pi](https://github.com/Ogeon/rust-on-raspberry-pi) - Ogeon
* [Taking Rust everywhere with rustup](http://blog.rust-lang.org/2016/05/13/rustup.html) - [Brian Anderson]
* [Why is a Rust executable large?](https://lifthrasiir.github.io/rustlog/why-is-a-rust-executable-large.html) - Kang Seonghoon

## CI / Testing

* [Helping Travis catch the rustc train part 1](https://huonw.github.io/blog/2015/04/helping-travis-catch-the-rustc-train/) | [part 2](https://huonw.github.io/blog/2015/05/travis-on-the-train-part-2/) - [Huon Wilson][]
* [Rust, Travis, and Github Pages](http://hoverbear.org/2015/03/07/rust-travis-github-pages/) - [Andrew Hobden][]
* [Shave Some Time From Your Travis Builds](https://llogiq.github.io/2016/07/05/travis.html) - [Llogiq][]
* [How to collect test coverages for a rust project](https://users.rust-lang.org/t/tutorial-how-to-collect-test-coverages-for-rust-project/650) - lifthrasiir
* [Rust Code Coverage Guide: kcov + Travis CI + Codecov / Coveralls](http://sunjay.ca/2016/07/25/rust-code-coverage) - Sunjay Varma

## Comparison with Other Languages

| Languages        | Links     |
| ---------------- | --------------- |
| C# | <ul><li>[Exploring Rust (from C#)](http://nblumhardt.com/2016/03/exploring-rust/) - Nicholas Blumhardt</li></ul> |
| C/C++ | <ul><li>[Rust for C++ Programmers](http://aminb.gitbooks.io/rust-for-c/content/) - [Nick Cameron][]</li><li>[On rust's memory management. Mainly for C/C++ programmers](http://blog.zgtm.de/1) - Robert</li></ul> |
| Clojure | <ul><li>[Rust for Clojurists](https://gist.github.com/oakes/4af1023b6c5162c6f8f0) - Zach Oakes</li></ul> |
| Go | <ul><li>[A Rust Contributor Tries Their Hand at Go](http://www.polyglotweekly.com/2015/04/24/thoughts-of-a-rustacean-learning-go.html) - [Manish Goregaokar][]</li></ul> |
| Java | <ul><li>[Comparing Rust and Java](https://llogiq.github.io/2016/02/28/java-rust.html) - [Llogiq][]</li><li>[A light comparison between Rust and Java generics and type system features.](https://gist.github.com/Kimundi/8391398) - Marvin Löbel</li></ul>  |
| JavaScript | <ul><li>[Rust's Ownership model for JavaScript developers](http://blog.thoughtram.io/rust/2015/05/11/rusts-ownership-model-for-javascript-developers.html) - [Christoph Burgdorf][]</li><li>[Rust for Node developers](https://github.com/Mercateo/rust-for-node-developers) - Donald Pipowitch</li></ul> |
| Nim | <ul><li>[A Quick Comparison of Nim vs. Rust](https://arthurtw.github.io/2015/01/12/quick-comparison-nim-vs-rust.html) - Arthur Liao</li></ul> |
| Python | <ul><li>[Rust for Python Programmers](http://lucumr.pocoo.org/2015/5/27/rust-for-pythonistas/) - Armin Ronacher</li></ul> |
| Ruby | <ul><li>[Rust for Rubyists](http://www.rustforrubyists.com/) - [Steve Klabnik][]</li></ul> |
| Swift | <ul><li>[A Swift guide to Rust](http://faq.sealedabstract.com/rust/) - sealedabstract</li><li>[Rust and Swift](http://www.chriskrycho.com/rust-and-swift.html) - [Chris Krycho][]</li></ul> |

## Applications / Libraries / Tools

See the awesome repo [kud1ing/awesome-rust](https://github.com/kud1ing/awesome-rust)

## Language stuff

### Closures

* [Finding Closure in Rust](https://huonw.github.io/blog/2015/05/finding-closure-in-rust/) - [Huon Wilson][]
* [Defaulting to Thread-Safety: Closures and Concurrency](https://huonw.github.io/blog/2015/05/defaulting-to-thread-safety/) - [Huon Wilson][]
* [How to pass a closure into a trait object](http://camjackson.net/post/rust-lang-how-to-pass-a-closure-into-a-trait-object) - Cam Jackson
* [Practical differences between Rust closures and functions](https://ricardomartins.cc/2015/10/12/practical_differences_between_rust_closures_and_functions) - Ricardo Martins
* [How Rust Achieves Thread Safety](https://manishearth.github.io/blog/2015/05/30/how-rust-achieves-thread-safety/) - [Manish Goregaokar][]

### Enums

* [Virtual Structs part 1](http://smallcultfollowing.com/babysteps/blog/2015/05/05/where-rusts-enum-shines/) | [part 2](http://smallcultfollowing.com/babysteps/blog/2015/05/29/classes-strike-back/) | [part 3](http://smallcultfollowing.com/babysteps/blog/2015/08/20/virtual-structs-part-3-bringing-enums-and-structs-together/) - [Niko Matsakis][]

### Iterators

* [A Journey into Iterators](http://hoverbear.org/2015/05/02/a-journey-into-iterators/) - [Andrew Hobden][]
* [Effectively Using Iterators In Rust](http://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html) - [Herman J. Radtke III][]
* [for loops in Rust](http://xion.io/post/code/rust-for-loop.html) - Karol Kuczmarski

### Lifetime

* [Where Rust Really Shines](https://manishearth.github.io/blog/2015/05/03/where-rust-really-shines/) - [Manish Goregaokar][]
* [Understanding Lifetime in Rust part 1](https://mobiarch.wordpress.com/2015/06/29/understanding-lifetime-in-rust-part-i/) | [part 2](https://mobiarch.wordpress.com/2015/07/08/understanding-lifetime-in-rust-part-ii-3/) - Bibhas Bhattacharya
* [Rust Lifetimes](http://www.charlesetc.com/rust/2015/10/29/) - Charles

### Macros

* [A Practical Intro to Macros in Rust 1.0](https://danielkeep.github.io/practical-intro-to-macros.html) - [Daniel Keep][]
* [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/) - [Daniel Keep][]
* [Macros in Rust part 1](http://www.ncameron.org/blog/macros-in-rust-pt1/) | [part 2](http://www.ncameron.org/blog/macros-in-rust-pt2/) | [part 3](http://ncameron.org/blog/macros-in-rust-pt3/) | [part 4](http://ncameron.org/blog/macros-in-rust-pt4/) - [Nick Cameron][]
* [How do I use the Standard Library Macros in Rust?](http://mgattozzi.github.io/2016/06/01/how-do-i-std-macros.html) - [Michael Gattozzi][]

### MIR

* [Introducing MIR](http://blog.rust-lang.org/2016/04/19/MIR.html) - [Niko Matsakis][]

### Monads

* [Option Type part 1](http://blog.8thlight.com/dave-torre/2015/03/11/the-option-type.html) | [part 2](http://blog.8thlight.com/uku-taht/2015/04/29/using-the-option-type-effectively.html) - 8thlight
* [old] [Option Monads in Rust](http://hoverbear.org/2014/08/12/option-monads-in-rust/) - [Andrew Hobden][]

### Ownership / Concurrency

* [official] [Fearless Concurrency with Rust](http://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html) - [Aaron Turon][]
* [Rust ownership, the hard way](http://chrismorgan.info/blog/rust-ownership-the-hard-way.html) - [Chris Morgan][]
* [An alternative introduction to Rust](http://words.steveklabnik.com/a-new-introduction-to-rust) - [Steve Klabnik][]
* [The Problem With Single-threaded Shared Mutability](https://manishearth.github.io/blog/2015/05/17/the-problem-with-shared-mutability/) - [Manish Goregaokar][]
* [Wrapper Types in Rust: Choosing Your Guarantees](https://manishearth.github.io/blog/2015/05/27/wrapper-types-in-rust-choosing-your-guarantees/) - [Manish Goregaokar][]
* [Strategies for solving 'cannot move out of' borrowing errors in Rust](http://hermanradtke.com/2015/06/09/strategies-for-solving-cannot-move-out-of-borrowing-errors-in-rust.html) - [Herman J. Radtke III][]
* [Why Rust's ownership/borrowing is hard](http://softwaremaniacs.org/blog/2016/02/12/ownership-borrowing-hard/en/) - Ivan Sagalaev
* [& vs. ref in Rust patterns](http://xion.io/post/code/rust-patterns-ref.html) - Karol Kuczmarski
* [Interior mutability in Rust: what, why, how?](https://ricardomartins.cc/2016/06/08/interior-mutability) | [part 2](https://ricardomartins.cc/2016/06/25/interior-mutability-thread-safety) | [part 3](https://ricardomartins.cc/2016/07/11/interior-mutability-behind-the-curtain) - Ricardo Martins
* [Rust Means Never Having to Close a Socket](http://blog.skylight.io/rust-means-never-having-to-close-a-socket/) - [Yehuda Katz][]
* [Understanding Lifetimes in Rust, part 1](https://mobiarch.wordpress.com/2015/06/29/understanding-lifetime-in-rust-part-i/) | [part 2](https://mobiarch.wordpress.com/2015/07/08/understanding-lifetime-in-rust-part-ii-3/) - Bibhas Bhattacharya
* [Some Notes on `Send` and `Sync`](https://huonw.github.io/blog/2015/02/some-notes-on-send-and-sync/) - [Huon Wilson][]
* [Moving, Cloning, and Copying Coloring Books in Rust](http://jeenalee.com/2016/08/29/move-clone-copy.html) - [Jeena Lee][]

### Privacy

* [Structure literals vs constructors in Rust](http://words.steveklabnik.com/structure-literals-vs-constructors-in-rust) - [Steve Klabnik][]

### Strings

* [String vs &str in Rust functions part 1](http://hermanradtke.com/2015/05/03/string-vs-str-in-rust-functions.html) | [part 2](http://hermanradtke.com/2015/05/06/creating-a-rust-function-that-accepts-string-or-str.html) | [part 3](http://hermanradtke.com/2015/05/29/creating-a-rust-function-that-returns-string-or-str.html) - [Herman J. Radtke III][]
* [From &str to Cow](http://blog.jwilm.io/from-str-to-cow/) - Joe Wilm
* [How do I convert a &str to a String in Rust?](http://mgattozzi.github.io/2016/05/26/how-do-i-str-string.html) - [Michael Gattozzi][]

### Syntax extensions

* [Syntax extensions and regular expressions for Rust](http://blog.burntsushi.net/rust-regex-syntax-extensions/) - [Andrew Gallant][]
* [How to Write a Rust Syntax Extension](http://brodoyouevencode.com/posts/how-to-write-a-rust-syntax-extension/) - [Gulshan Singh][]

### Traits

* [official] [Abstraction without overhead: traits in Rust](http://blog.rust-lang.org/2015/05/11/traits.html) - [Aaron Turon][]
* [A series on trait objects part 1](https://huonw.github.io/blog/2015/01/peeking-inside-trait-objects) | [part 2](https://huonw.github.io/blog/2015/01/the-sized-trait) | [part 3](https://huonw.github.io/blog/2015/01/object-safety) | [part 4](https://huonw.github.io/blog/2015/05/where-self-meets-sized-revisiting-object-safety/) - [Huon Wilson][]
* [Rust traits for developer friendly libraries](https://benashford.github.io/blog/2015/05/24/rust-traits-for-developer-friendly-libraries/) - [Ben Ashford][]
* [Traits and trait objects](http://xania.org/201506/traits-and-trait-objects) - Matt Godbolt
* [Rust's Built-in Traits, the When, How & Why](https://llogiq.github.io/2015/07/30/traits.html) - [Llogiq][]
* [Where are you From::from](http://llogiq.github.io/2015/11/27/from-into.html) - [Llogiq][]
* [Going down the rabbit hole with Rust traits](http://www.jonathanturner.org/2016/02/down-the-rabbit-hole-with-traits.html) - [Jonathan Turner][]

### Unsafe

* [Unsafe Rust: An Intro and Open Questions](http://cglab.ca/~abeinges/blah/rust-unsafe-intro/) - [Alexis Beingessner][]
* [Memory Leaks are Memory Safe](https://huonw.github.io/blog/2016/04/memory-leaks-are-memory-safe/) - [Huon Wilson][]
* [On Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/29/on-reference-counting-and-leaks/) - [Niko Matsakis][]
* [A Few More Remarks on Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/30/a-few-more-remarks-on-reference-counting-and-leaks/) - [Niko Matsakis][]
* [Pre-pooping Your Pants With Rust](http://cglab.ca/~abeinges/blah/everyone-poops/) - [Alexis Beingessner][]
* [Unsafe Abstractions](http://smallcultfollowing.com/babysteps/blog/2016/05/23/unsafe-abstractions/) - [Niko Matsakis][]
* [The "Tootsie Pop" Model for Unsafe Code](http://smallcultfollowing.com/babysteps/blog/2016/05/27/the-tootsie-pop-model-for-unsafe-code/) - [Niko Matsakis][]

## Playground

* [Rust Playground](https://play.rust-lang.org)
* [alternative](http://play.integer32.com/)

## Locale links

* [Brazilian Portuguese](pt_BR.md)
* [Chinese](zh_CN.md)
* [Danish](da_DK.md)
* [French](fr_FR.md)
* [German](de_DE.md)
* [Italian](it_IT.md)
* [Japanese] (ja_JP.md)
* [Korean](ko_KR.md)
* [Russian](ru_RU.md)
* [Spanish](es_ES.md)
* [Turkish](tr-TR.md)

## People

This is the official [Rust Team](http://www.rust-lang.org/team.html) and [Servo Team](https://github.com/orgs/servo/people)

You search for a rustacean ? [http://www.rustaceans.org/](http://www.rustaceans.org/)

You want to meet them IRL ? [Meetup groups][m], [community calendar][c]

Go to rusty events ? [RustCamp](http://rustcamp.com/), [RustFest](http://www.rustfest.eu/), [RustConf](http://rustconf.com/), [Rust Belt Rust](http://www.rust-belt-rust.com/)

You are looking for a job ? [Rust Community Job Board](https://rust.jobboard.io/)

You want to stay up to date ? [This Week in Rust](https://this-week-in-rust.org/), [This Week in Rust Docs](http://guillaumegomez.github.io/this-week-in-rust-docs/)

[m]: http://www.meetup.com/topics/rust/
[c]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com

### Famous Rustacean Bloggers

* [Andrew Gallant][] - [blog](http://blog.burntsushi.net/)
* [Andrew Hobden][] - [blog](http://hoverbear.org/tag/rust/)
* [Brian Anderson][] - [blog](https://brson.github.io/blog/index.html)
* [Christoph Burgdorf][] - [blog](https://cburgdorf.wordpress.com/)
* [Chris Morgan][] - [blog](http://chrismorgan.info/blog/tags/rust.html)
* [Felix S Klock II][] - [blog](http://blog.pnkfx.org/)
* [Huon Wilson][] - [blog](https://huonw.github.io/blog/)
* [Jonathan Turner][] - [blog](http://www.jonathanturner.org/)
* [Llogiq][] - [blog](http://llogiq.github.io/)
* [Manish Goregaokar][] - [blog](https://manishearth.github.io/)
* [Nick Cameron][] - [blog](http://featherweightmusings.blogspot.fr/)
* [Niko Matsakis][] - [blog](http://smallcultfollowing.com/babysteps/)
* [Patrick Walton][] - [blog](https://pcwalton.github.io/)
* [Yehuda Katz][] - [blog](http://yehudakatz.com/)
* [Steve Klabnik][] - [blog](http://words.steveklabnik.com/)

Don't forget [Ferris](http://www.rustacean.net/) the unofficial mascot.

## Tutorials & Workshop Materials

These are slides and materials from brick-and-mortar workshops about Rust.
While they're unlikely to help a student learning independently, they may be
of interest if you're running a workshop on Rust.

* Niko Matsakis's [rust tutorializer](https://github.com/nikomatsakis/rust-tutorializer) framework
* Niko Matsakis's [ownership, borrowing, traits, structs, and threading tutorials](https://github.com/nikomatsakis/rust-tutorials-keynote), keynote files
* Niko Matsakis's [concurrency tutorial](https://github.com/nikomatsakis/concurrency-tutorial) from December 2015
* Niko Matsakis's [Mozlando Tutorial](http://smallcultfollowing.com/20151209/) includes slides and play.rust-lang.org demos
* Jim Blandy's [exercises](https://github.com/jimblandy/exercises)
* Dan Callahan's [Python Rust FFI](https://github.com/callahad/python-rust-ffi) examples
* Nick Cameron's [oopsla slides and exercises](http://ncameron.org/oopsla15.html)
* Florian Gilcher's [mailbox tutorial](https://github.com/skade/mailbox) takes Hello World to a whole new concurrent and networked level
* Carol Nichols' [Intro to Rust](https://github.com/carols10cents/intro-to-rust) that presents the guessing game and ownership in a similar manner as the book

<!-- Rustaceans -->
[Aaron Turon]: https://github.com/aturon
[Alex Crichton]: https://github.com/alexcrichton
[Alexis Beingessner]: https://github.com/Gankro
[Andrew Gallant]: https://github.com/BurntSushi
[Andrew Hobden]: https://github.com/Hoverbear
[Ben Ashford]: https://github.com/benashford
[Brian Anderson]: https://github.com/brson
[Carl Lerche]: https://github.com/carllerche
[Chris Krycho]: https://github.com/chriskrycho
[Chris Morgan]: https://github.com/chris-morgan
[Christoph Burgdorf]: https://github.com/cburgdorf
[Daniel Keep]: https://github.com/DanielKeep
[Dan Callahan]: https://github.com/callahad
[Eduard Burtescu]: https://github.com/eddyb
[Felix S Klock II]: https://github.com/pnkfelix
[Gulshan Singh]: https://github.com/gsingh93
[Herman J. Radtke III]: https://github.com/hjr3
[Jakub Bukaj]: https://github.com/jakub-
[Jeena Lee]: https://github.com/jeenalee
[Jim Blandy]: https://github.com/jimblandy
[Jorge Aparicio]: https://github.com/japaric
[Josh Matthews]: https://github.com/jdm
[Jonathan Turner]: https://github.com/jonathandturner
[Llogiq]: https://github.com/llogiq
[Luqman Aden]: https://github.com/luqmana
[Huon Wilson]: https://github.com/huonw
[Manish Goregaokar]: https://github.com/Manishearth
[Michael Gattozzi]: https://github.com/mgattozzi
[Nick Cameron]: https://github.com/nrc
[Niko Matsakis]: https://github.com/nikomatsakis
[Patrick Walton]: https://github.com/pcwalton
[Seo Sanghyeon]: https://github.com/sanxiyn
[Simon Sapin]: https://github.com/SimonSapin
[Steve Klabnik]: https://github.com/steveklabnik
[Steven Fackler]: https://github.com/sfackler
[Tetsuharu OHZEKI]: https://github.com/saneyuki
[Yehuda Katz]: https://github.com/wycats
