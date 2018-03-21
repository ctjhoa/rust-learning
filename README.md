# rust-learning [![Build Status](https://travis-ci.org/ctjhoa/rust-learning.svg?branch=master)](https://travis-ci.org/ctjhoa/rust-learning)

A bunch of links to blog posts, articles, videos, etc for learning Rust. Feel free to submit a pull request if you have some links/resources to add. Also, I try to verify that the articles below have some real content (i.e. aren't 2 paragraph blog posts with little information) to ensure I'm not listing "fluff" pieces. If you have an idea for a better way to organize these links, please let me know.

## Introduction

*Do you need to be convinced that Rust worth learning?* Let us show you the [True Nature of the Force](https://brson.github.io/fireflowers/)

The main documentation is always the best beginning, so if you haven't read yet, start by reading [Rust docs](https://www.rust-lang.org/en-US/documentation.html). You also have ebook versions of the doc [here](http://killercup.github.io/trpl-ebook/) and [there](https://github.com/lise-henry/books/).

### Tags meanings

* :star: Something made by a rust team member.
* :end: Concepts are still useful but code could not compile.
* :soon: Work In Progress.

## Table of Contents

* [Books](#books)
* [Videos](#videos)
  * [Playlists](#playlists)
  * [Presentations](#presentations)
* [Podcasts](#podcasts)
* [Rust in practice](#rust-in-practice)
* [Best Practices/Style Guides](#best-practicesstyle-guides)
* [Cheat sheets](#cheat-sheets)
* [Rust internals](#rust-internals)
* [Compilation](#compilation)
* [FFI](#ffi)
* [CI / Testing](#ci--testing)
* [Debug / Profiling](#debug--profiling)
* [Are we ... yet?](#are-we--yet)
* [Comparison with Other Languages](#comparison-with-other-languages)
* [Applications / Libraries / Tools](#applications--libraries--tools)
* [Language stuff](#language-stuff)
  * [Closures](#closures)
  * [Documentation](#documentation)
  * [Enums](#enums)
  * [Iterators](#iterators)
  * [Lifetime](#lifetime)
  * [Macros](#macros)
  * [MIR](#mir)
  * [Modules](#modules)
  * [Monads](#monads)
  * [Ownership / Concurrency](#ownership--concurrency)
  * [Privacy](#privacy)
  * [Strings](#strings)
  * [Syntax extensions](#syntax-extensions)
  * [Traits](#traits)
  * [Unsafe](#unsafe)
* [Playground](#playground)
* [Locale links](#locale-links)
* [People](#people)
  * [Famous Rustacean Bloggers](#famous-rustacean-bloggers)
* [Tutorials & Workshop Materials](#tutorials--workshop-materials)
* [Similar projects](#similar-projects)

## Books

* :star: [The Rust Programming Language 1st edition](https://doc.rust-lang.org/stable/book/first-edition/) - [repo](https://github.com/rust-lang/book/tree/master/first-edition)
* :soon: :star: [The Rust Programming Language 2nd edition](https://doc.rust-lang.org/stable/book/second-edition/) - [repo](https://github.com/rust-lang/book/tree/master/second-edition) ([Paper edition](https://www.nostarch.com/Rust))
* :star: [The Rust Reference](https://doc.rust-lang.org/stable/reference/) - [repo](https://github.com/rust-lang-nursery/reference)
* :star: [The Rustonomicon - The Dark Arts of Advanced and Unsafe Rust Programming](https://doc.rust-lang.org/stable/nomicon/) - [repo](https://github.com/rust-lang-nursery/nomicon)
* :star: [The Unstable Book](https://doc.rust-lang.org/stable/unstable-book/) - [repo](https://github.com/rust-lang/rust/tree/master/src/doc/unstable-book)
* :star: [Why Rust?](http://www.oreilly.com/programming/free/files/why-rust.pdf) - [Jim Blandy][]
* [Rust-101](https://www.ralfj.de/projects/rust-101/main.html) - Ralf Jung
* [Rust Essentials](https://www.packtpub.com/application-development/rust-essentials-second-edition) -  Ivo Balbaert
* :soon: [Programming Rust](http://shop.oreilly.com/product/0636920040385.do) - [Jim Blandy][]
* [Mastering Rust](https://www.packtpub.com/application-development/mastering-rust) - Vesa Kaihlavirta
* :star: [Rust Anthology](https://github.com/brson/rust-anthology) - [Brian Anderson][]
* :soon: [Rust in Action](https://www.manning.com/books/rust-in-action) - TS McNamara
* [Network Programming in Rust](https://www.packtpub.com/application-development/network-programming-rust) - Abhishek Chanda
* [Learning Rust](https://www.packtpub.com/application-development/learning-rust) -  Paul Johnson, Vesa Kaihlavirta
* [Rust Cookbook](https://www.packtpub.com/application-development/rust-cookbook) -  Vigneshwer Dhinakaran
* [Learning Rust](https://learning-rust.github.io/) - [Dumindu Madunuwan][]
* [A Gentle Introduction To Rust](http://stevedonovan.github.io/rust-gentle-intro/readme.html) - [Steve Donovan][]
* [Step Ahead with Rust](https://www.amazon.com/Step-Ahead-Rust-Jonathan-Creekmore/dp/0999361805/) - Jonathan Creekmore
* :star: [Rust Programming By Example](https://www.amazon.com/Rust-Programming-Example-Guillaume-Gomez/dp/1788390636) - Guillaume Gomez and Antoni Boucher

## Videos

### Playlists

* :star: [Rust and the Future of Systems Programming](https://www.youtube.com/playlist?list=PLo3w8EB99pqJ74XIGe72c9hBZWz9Y16cY) - Mozilla
* [air.mozilla Rust's meetups](https://air.mozilla.org/channels/rust/)
* [RustFest Zürich 2017](https://www.youtube.com/watch?v=jywiVWKm1TI&list=PL85XCvVPmGQj9mqbJizw-zi-EhcpS5jTP)
* [J M Archer Tutorials](https://www.youtube.com/playlist?list=PLTOeCUgrkpMNEHx6j0vCH0cuyAIVZadnc) - J M Archer
* [ABitWiseGuy Tutorials](https://www.youtube.com/watch?v=y-ks-_VDkiA&list=PL0Fqs05rod8D80WKBCeT326CT8vcAm_N9) - ABitWiseGuy
* [dcode Tutorials](https://www.youtube.com/watch?v=vOMJlQ5B-M0&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL) - dcode
* [Tensor Programming Tutorials](https://www.youtube.com/watch?v=EYqceb2AnkU&list=PLJbE2Yu2zumDF6BX6_RdPisRVHgzV02NW) - Tensor Programming
* [Hello Rust!](https://www.youtube.com/channel/UCZ_EWaQZCZuGGfnuqUoHujw) - Matthias Endler

### Presentations

* 2017-06-20 - :star: [Rust: Putting Ownership to Use](https://www.youtube.com/watch?v=wXoY91w4Agk) - [Niko Matsakis][]
* 2017-01-20 - [Rust 101](https://www.youtube.com/watch?v=FMqydRampuo) - E. Dunham
* 2016-09-28 - [Mozilla's Rust and why we love it](http://blog.cambridgeconsultants.com/wireless-product-development/presentation-mozillas-rust-and-why-we-love-it/) - Cambridge Consultants
* 2016-09-25 - :star: [into_rust() - Screencasts for learning rust!](http://intorust.com/) - [Niko Matsakis][]
* 2016-08-28 - :star: [Rust: Safe and Scalable Systems Programming](https://www.youtube.com/watch?v=GbWECt0M3CI) - [Alex Crichton][]
* 2016-06-21 - :star: [The History of Rust](https://www.youtube.com/watch?v=79PSagCD_AY) - [Steve Klabnik][]
* 2015-08-01 - :star: [RustCamp 2015](http://confreaks.tv/events/rustcamp2015)
* 2015-06-22 - [LambdaConf 2015 - In Rust We Trust](https://www.youtube.com/watch?v=-dxqbhLIgdM) - Alex Burkhart
* 2015-06-13 - :star: [What Is Rust?](http://www.infoq.com/presentations/rust-gc) - [Yehuda Katz][]
* 2015-04-11 - [My Python's a little Rust-y](https://www.youtube.com/watch?v=3CwJ0MH-4MA) - [Dan Callahan][]
* 2015-03-12 - :star: [Stanford Seminar](https://www.youtube.com/watch?v=O5vzLKg7y-k) - [Aaron Turon][]

## Podcasts

* [New Rustacean](http://www.newrustacean.com) - [Chris Krycho][]
* [The Request for Explanation Podcast: A weekly discussion of Rust RFCs](https://request-for-explanation.github.io/podcast/) - [Manish Goregaokar][]
* [Rusty Spike Podcast – A podcast for Rust and Servo](https://rusty-spike.blubrry.net/) - [Jonathan Turner][]

## Rust in practice

* :star: [rustbyexample](http://rustbyexample.com/) - [Jorge Aparicio][] and [Steve Klabnik][]
* [rosettacode](https://github.com/Hoverbear/rust-rosetta) - [Andrew Hobden][]
* [Why your first FizzBuzz implementation may not work](http://chrismorgan.info/blog/rust-fizzbuzz.html) - [Chris Morgan][]
* :star: [An annotation of the Rust standard library](https://github.com/brson/annotated-std-rs) - [Brian Anderson][]
* [ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust) - gifnksm
* [Advent of Code](https://github.com/LD250/adventofcode_rust) - Denys Levchenko
* [Rust in Detail: Writing Scalable Chat Service from Scratch](https://nbaksalyar.github.io/) - Nikita Baksalyar
* :star: [rustlings: small rust exercises](https://github.com/carols10cents/rustlings) - [Carol Nichols][]
* [Learning Rust With Entirely Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/) - [Alexis Beingessner][]
* :star: [Let's build a browser engine!](http://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html) - Matt Brubeck
* [Understanding Over Guesswork](http://hoverbear.org/2015/09/12/understand-over-guesswork/) - [Andrew Hobden][]
* [Writing an OS in Rust 1st edition](http://os.phil-opp.com/) [2nd edition](https://os.phil-opp.com/second-edition/) - Philipp Oppermann
* [Creating Nintendo 64 emulator from scratch in Rust!](https://www.youtube.com/playlist?list=PL-sXmdrqqYYcznDg4xwAJWQgNL2gRray2) - Jake Taylor
* [The Many Kinds of Code Reuse in Rust](http://cglab.ca/~abeinges/blah/rust-reuse-and-recycle/) - [Alexis Beingessner][]
* [Make a Lisp](https://github.com/kanaka/mal/tree/master/rust) - Joel Martin
* :star: [Modeling Graphs in Rust Using Vector Indices](http://smallcultfollowing.com/babysteps/blog/2015/04/06/modeling-graphs-in-rust-using-vector-indices/) - [Niko Matsakis][]
* [24 days of Rust series](https://siciarz.net/tag/24%20days%20of%20rust/) - Zbigniew Siciarz
* :star: [Rust Cookbook](https://github.com/brson/rust-cookbook)
* :star: [Rust and CSV Parsing](http://blog.burntsushi.net/csv/) - [Andrew Gallant][]
* [Algorithm Cookbook in Rust](https://github.com/EbTech/rust-algorithms) - Aram Ebtekar
* :star: [stdx - The missing batteries of Rust](https://github.com/brson/stdx) - [Brian Anderson][]
* [Writing a Command Line Tool in Rust](http://mattgathu.github.io/writing-cli-app-rust/) - Matt Gathu
* [Rust - exercism.io](http://exercism.io/languages/rust/about)
* [Intro to Rust using Permission-based Authorization](http://daringordon.com/authz_rs_tutorial/) - Darin Gordon
* [Building a DNS server in Rust](https://github.com/EmilHernvall/dnsguide) - Emil Hernvall

## Best Practices/Style Guides

* :star: [Rust Design Patterns](https://github.com/nrc/patterns) - [Nick Cameron][]
* :star: [Error Handling in Rust](http://blog.burntsushi.net/rust-error-handling/) - [Andrew Gallant][]
* [Reading Rust Function Signatures](http://hoverbear.org/2015/07/10/reading-rust-function-signatures/) - [Andrew Hobden][]
* [Good Practices for Writing Rust Libraries](https://pascalhertleif.de/artikel/good-practices-for-writing-rust-libraries/) - [Pascal Hertleif][]
* [Rustic Bits](https://llogiq.github.io/2016/02/11/rustic.html) - [Llogiq][]
* [Pretty State Machine Patterns in Rust](https://hoverbear.org/2016/10/12/rust-state-machine-pattern/) - [Andrew Hobden][]
* [Elegant Library APIs in Rust](https://scribbles.pascalhertleif.de/elegant-apis-in-rust.html) - [Pascal Hertleif][]
* :star: [Rust API guidelines](https://github.com/brson/rust-api-guidelines) - [Brian Anderson][]
* [Rust Performance Pitfalls](https://llogiq.github.io/2017/06/01/perf-pitfalls.html) - [Llogiq][]

## Cheat sheets

* :star: [Syntax Index](https://doc.rust-lang.org/book/syntax-index.html)
* [The Periodic Table of Rust Types](http://cosmic.mearie.org/2014/01/periodic-table-of-rust-types/) - Kang Seonghoon
* [Rust Iterator Cheat Sheet](https://danielkeep.github.io/itercheat_baked.html) - [Daniel Keep][]
* [Rust String Conversions Cheat Sheet](https://docs.google.com/spreadsheets/d/19vSPL6z2d50JlyzwxariaYD6EU2QQUQqIDOGbiGQC7Y/pubhtml?gid=0&single=true) - GavinB
* [Rustic Symmetries](https://github.com/kmcallister/rustic-symmetries/blob/master/README.md#rustic-symmetries) - kmc
* [Rust Container Cheat Sheet](https://docs.google.com/presentation/d/1q-c7UAyrUlM-eZyTo1pd8SZ0qwA_wYxmPZVOQkoDmH4/edit?usp=sharing) - Raph Levien
* [Graphical depiction of ownership and borrowing in Rust](https://rufflewind.com/img/rust-move-copy-borrow.png) - Phil Ruffwind

## Rust internals

* :star: [Rust RFCs](https://github.com/rust-lang/rfcs) and [Accepted RFCs](https://rust-lang.github.io/rfcs/)
* :star: [Rust Forge](https://forge.rust-lang.org/)
* :star: [Internals Forum](https://internals.rust-lang.org/)

## Compilation

* [rust-cross, Everything you need to know about cross compiling Rust programs!](https://github.com/japaric/rust-cross) - [Jorge Aparicio][]
* [How to cross compile Rust from OS X to FreeBSD](https://github.com/yohanesu75/crossrust) - yohanesu75
* [Cross Compiling for Raspberry Pi](https://github.com/Ogeon/rust-on-raspberry-pi) - Ogeon
* :star: [Taking Rust everywhere with rustup](http://blog.rust-lang.org/2016/05/13/rustup.html) - [Brian Anderson][]
* [Why is a Rust executable large?](https://lifthrasiir.github.io/rustlog/why-is-a-rust-executable-large.html) - Kang Seonghoon
* [Using Rust in Windows](http://www.jonathanturner.org/2017/03/rust-in-windows.html) - [Jonathan Turner][]
* [Rust your ARM microcontroller!](http://blog.japaric.io/quickstart/) - [Jorge Aparicio][]
* [Cross-compiling Rust for the Raspberry Pi on macOS](https://akappel.github.io/2017/11/07/rpi-crosstool.html) - Adrian Kappel

## FFI

* 2017-11-22 - [Writing fast and safe native Node.js modules with Rust](https://blog.risingstack.com/node-js-native-modules-with-rust/) - Peter Czibik
* 2017-09-21 - [Building and Deploying a Rust library on Android](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-21-rust-on-android.html) - Emily Toop
* 2017-09-06 - [Building and Deploying a Rust library on iOS](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-06-rust-on-ios.html) - Emily Toop
* [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/?updated=2015-11-08) - Jake Goulding
* [The Rust FFI Guide - using unsafe for fun and profit](https://michael-f-bryan.github.io/rust-ffi-guide/) - Michael-F-Brya

## CI / Testing

* [Helping Travis catch the rustc train part 1](https://huonw.github.io/blog/2015/04/helping-travis-catch-the-rustc-train/) | [part 2](https://huonw.github.io/blog/2015/05/travis-on-the-train-part-2/) - [Huon Wilson][]
* [Rust, Travis, and Github Pages](http://hoverbear.org/2015/03/07/rust-travis-github-pages/) - [Andrew Hobden][]
* [Shave Some Time From Your Travis Builds](https://llogiq.github.io/2016/07/05/travis.html) - [Llogiq][]
* [How to collect test coverages for a rust project](https://users.rust-lang.org/t/tutorial-how-to-collect-test-coverages-for-rust-project/650) - lifthrasiir
* [Rust Code Coverage Guide: kcov + Travis CI + Codecov / Coveralls](http://sunjay.ca/2016/07/25/rust-code-coverage) - Sunjay Varma
* [Rust Performance Testing on Travis CI](https://beachape.com/blog/2016/11/02/rust-performance-testing-on-travis-ci/) - Lloyd
* [Ensuring Beautiful Commits with rustfmt and Travis-CI](http://kneit.in/2016/11/26/rustfmt-in-travisci.html) - Kyle Kneitinger
* [Great Rust CI ](https://dev.to/cad97/great-rust-ci-1fk6) - Christopher Durham

## Debug / Profiling

* [Debugging a segfault in my Rust program](https://jvns.ca/blog/2017/12/23/segfault-debugging/) - Julia Evans
* [Compiler Explorer - See Rust code as assembly](https://rust.godbolt.org/)
* [Profiling Rust applications on Linux](http://llogiq.github.io/2015/07/15/profiling.html) - [Llogiq][]

## Are we ... yet?

* [Are we web yet?](http://www.arewewebyet.org/)
* [Are we (I)DE yet?](https://areweideyet.com/)
* [Are we game yet?](http://arewegameyet.com/)
* [Are we learning yet?](http://www.arewelearningyet.com/)
* [Not-Yet-Awesome Rust](https://github.com/ErichDonGubler/not-yet-awesome-rust)

## Comparison with Other Languages

* [Rust::from(lang)](https://github.com/mgattozzi/rust-from-lang) - [Michael Gattozzi][]
* Others:

| Languages       | Links                                    |
| --------------- | ---------------------------------------- |
| C#              | <ul><li>[Exploring Rust (from C#)](http://nblumhardt.com/2016/03/exploring-rust/) - Nicholas Blumhardt</li></ul> |
| C/C++           | <ul><li>[Rust For Systems Programmers](https://github.com/nrc/r4cppp) & [Rust for C++ Programmers](https://www.gitbook.com/book/aminb/rust-for-c/details) - [Nick Cameron][]</li><li>[On rust's memory management. Mainly for C/C++ programmers](http://blog.zgtm.de/1) - Robert</li><li>[I used to use pointers - now what?](https://github.com/diwic/reffers-rs/blob/master/docs/Pointers.md) - diwic</li></ul> |
| Clojure         | <ul><li>[Rust for Clojurists](https://gist.github.com/oakes/4af1023b6c5162c6f8f0) - Zach Oakes</li></ul> |
| Java/Scala            | <ul><li>[Comparing Rust and Java](https://llogiq.github.io/2016/02/28/java-rust.html) - [Llogiq][]</li><li>[A light comparison between Rust and Java generics and type system features.](https://gist.github.com/Kimundi/8391398) - Marvin Löbel</li><li>[Rust: A Scala Engineer's Perspective](https://beachape.com/blog/2017/05/24/rust-from-scala/) - Lloyd </li></ul> |
| JavaScript      | <ul><li>[Rust's Ownership model for JavaScript developers](http://blog.thoughtram.io/rust/2015/05/11/rusts-ownership-model-for-javascript-developers.html) - [Christoph Burgdorf][]</li><li>[Rust for Node developers](https://github.com/Mercateo/rust-for-node-developers) - Donald Pipowitch</li></ul> |
| Nim             | <ul><li>[A Quick Comparison of Nim vs. Rust](https://arthurtw.github.io/2015/01/12/quick-comparison-nim-vs-rust.html) - Arthur Liao</li></ul> |
| OCaml / Haskell | <ul><li>[Rust for functional programmers](http://science.raphael.poss.name/rust-for-functional-programmers.html)</li></ul> |
| Python          | <ul><li>[Rust for Python Programmers](http://lucumr.pocoo.org/2015/5/27/rust-for-pythonistas/) - Armin Ronacher</li><li>[py2rs](https://github.com/rochacbruno/py2rs) - Bruno Rocha</li></ul> |
| Ruby            | <ul><li>[Rust for Rubyists](http://www.rustforrubyists.com/) - [Steve Klabnik][]</li></ul> |
| Swift           | <ul><li>[A Swift guide to Rust](http://faq.sealedabstract.com/rust/) - sealedabstract</li><li>[Rust and Swift](http://www.chriskrycho.com/rust-and-swift.html) - [Chris Krycho][]</li></ul> |
| Erlang           | <ul><li>[A Comparison between erlang and rust starting from language semantics to runtime features, performance etc..](https://www.infoq.com/articles/rust-erlang-comparison) - Krishna Kumar Thokala</li></ul> |

## Applications / Libraries / Tools

See repos [kud1ing/awesome-rust](https://github.com/kud1ing/awesome-rust) & [awesomo
/rust](https://github.com/lk-geimfari/awesomo/blob/master/languages/RUST.md)

## Language stuff

### Closures

* [Finding Closure in Rust](https://huonw.github.io/blog/2015/05/finding-closure-in-rust/) - [Huon Wilson][]
* [Defaulting to Thread-Safety: Closures and Concurrency](https://huonw.github.io/blog/2015/05/defaulting-to-thread-safety/) - [Huon Wilson][]
* [How to pass a closure into a trait object](http://camjackson.net/post/rust-lang-how-to-pass-a-closure-into-a-trait-object) - Cam Jackson
* [Practical differences between Rust closures and functions](https://ricardomartins.cc/2015/10/12/practical_differences_between_rust_closures_and_functions) - Ricardo Martins
* :star: [How Rust Achieves Thread Safety](https://manishearth.github.io/blog/2015/05/30/how-rust-achieves-thread-safety/) - [Manish Goregaokar][]

### Documentation

* :star: [Writing Documentation in Rust](https://facility9.com/2016/05/writing-documentation-in-rust/) - [Jeremiah Peschka][]

### Enums

* :star: [Virtual Structs part 1](http://smallcultfollowing.com/babysteps/blog/2015/05/05/where-rusts-enum-shines/) | [part 2](http://smallcultfollowing.com/babysteps/blog/2015/05/29/classes-strike-back/) | [part 3](http://smallcultfollowing.com/babysteps/blog/2015/08/20/virtual-structs-part-3-bringing-enums-and-structs-together/) - [Niko Matsakis][]

### Iterators

* [A Journey into Iterators](http://hoverbear.org/2015/05/02/a-journey-into-iterators/) - [Andrew Hobden][]
* [Effectively Using Iterators In Rust](http://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html) - [Herman J. Radtke III][]
* [for loops in Rust](http://xion.io/post/code/rust-for-loop.html) - Karol Kuczmarski
* [Iteration patterns for Result & Option](http://xion.io/post/code/rust-iter-patterns.html) - Karol Kuczmarski
* [Little tour of multiple iterators implementation in Rust](https://blog.guillaume-gomez.fr/articles/2017-03-09+Little+tour+of+multiple+iterators+implementation+in+Rust) - Guillaume Gomez
* [rust-iterators](https://github.com/rustomax/rust-iterators/) - Max Skybin

### Lifetime

* :star: [Where Rust Really Shines](https://manishearth.github.io/blog/2015/05/03/where-rust-really-shines/) - [Manish Goregaokar][]
* [Understanding Lifetime in Rust part 1](https://mobiarch.wordpress.com/2015/06/29/understanding-lifetime-in-rust-part-i/) | [part 2](https://mobiarch.wordpress.com/2015/07/08/understanding-lifetime-in-rust-part-ii-3/) - Bibhas Bhattacharya
* [Rust Lifetimes](http://www.charlesetc.com/rust/2015/10/29/) - Charles

### Macros

* [A Practical Intro to Macros in Rust 1.0](https://danielkeep.github.io/practical-intro-to-macros.html) - [Daniel Keep][]
* [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/) - [Daniel Keep][]
* :star: [Macros in Rust part 1](http://www.ncameron.org/blog/macros-in-rust-pt1/) | [part 2](http://www.ncameron.org/blog/macros-in-rust-pt2/) | [part 3](http://ncameron.org/blog/macros-in-rust-pt3/) | [part 4](http://ncameron.org/blog/macros-in-rust-pt4/) - [Nick Cameron][]
* [How do I use the Standard Library Macros in Rust?](https://mgattozzi.com/how-do-i-std-macros) - [Michael Gattozzi][]
* [Writing complex macros in Rust: Reverse Polish Notation](https://rreverser.com/writing-complex-macros-in-rust/) - Ingvar Stepanyan

### MIR

* :star: [Introducing MIR](http://blog.rust-lang.org/2016/04/19/MIR.html) - [Niko Matsakis][]

### Modules

* [Rust Module Essentials ](https://dev.to/hertz4/rust-module-essentials-12oi) - Sam Pagenkopf

### Monads

* [Option Type part 1](http://blog.8thlight.com/dave-torre/2015/03/11/the-option-type.html) | [part 2](http://blog.8thlight.com/uku-taht/2015/04/29/using-the-option-type-effectively.html) - 8thlight
* :end: [Option Monads in Rust](http://hoverbear.org/2014/08/12/option-monads-in-rust/) - [Andrew Hobden][]
* [Russian Dolls and clean Rust code](https://mgattozzi.com/russian-dolls) - [Michael Gattozzi][]

### Ownership / Concurrency

* :star: [Fearless Concurrency with Rust](http://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html) - [Aaron Turon][]
* [Rust ownership, the hard way](http://chrismorgan.info/blog/rust-ownership-the-hard-way.html) - [Chris Morgan][]
* :star: [An alternative introduction to Rust](http://words.steveklabnik.com/a-new-introduction-to-rust) - [Steve Klabnik][]
* :star: [The Problem With Single-threaded Shared Mutability](https://manishearth.github.io/blog/2015/05/17/the-problem-with-shared-mutability/) - [Manish Goregaokar][]
* :star: [Wrapper Types in Rust: Choosing Your Guarantees](https://manishearth.github.io/blog/2015/05/27/wrapper-types-in-rust-choosing-your-guarantees/) - [Manish Goregaokar][]
* [Strategies for solving 'cannot move out of' borrowing errors in Rust](http://hermanradtke.com/2015/06/09/strategies-for-solving-cannot-move-out-of-borrowing-errors-in-rust.html) - [Herman J. Radtke III][]
* [Why Rust's ownership/borrowing is hard](http://softwaremaniacs.org/blog/2016/02/12/ownership-borrowing-hard/en/) - Ivan Sagalaev
* [& vs. ref in Rust patterns](http://xion.io/post/code/rust-patterns-ref.html) - Karol Kuczmarski
* [Interior mutability in Rust: what, why, how?](https://ricardomartins.cc/2016/06/08/interior-mutability) | [part 2](https://ricardomartins.cc/2016/06/25/interior-mutability-thread-safety) | [part 3](https://ricardomartins.cc/2016/07/11/interior-mutability-behind-the-curtain) - Ricardo Martins
* :star: [Rust Means Never Having to Close a Socket](http://blog.skylight.io/rust-means-never-having-to-close-a-socket/) - [Yehuda Katz][]
* [Understanding Lifetimes in Rust, part 1](https://mobiarch.wordpress.com/2015/06/29/understanding-lifetime-in-rust-part-i/) | [part 2](https://mobiarch.wordpress.com/2015/07/08/understanding-lifetime-in-rust-part-ii-3/) - Bibhas Bhattacharya
* [Some Notes on `Send` and `Sync`](https://huonw.github.io/blog/2015/02/some-notes-on-send-and-sync/) - [Huon Wilson][]
* [Sharing Coloring Books With Friends in Rust](http://jeenalee.com/2016/08/15/sharing-coloring-books-in-rust.html) - [Jeena Lee][]
* [Moving, Cloning, and Copying Coloring Books in Rust](http://jeenalee.com/2016/08/29/move-clone-copy.html) - [Jeena Lee][]
* [Ref patterns, destructuring, and invisible borrows](https://medium.com/@robertgrosse/ref-patterns-destructuring-and-invisible-borrows-2f8ae6902656) - Robert Grosse

### Privacy

* :star: [Structure literals vs constructors in Rust](http://words.steveklabnik.com/structure-literals-vs-constructors-in-rust) - [Steve Klabnik][]

### Strings

* [String vs &str in Rust functions part 1](http://hermanradtke.com/2015/05/03/string-vs-str-in-rust-functions.html) | [part 2](http://hermanradtke.com/2015/05/06/creating-a-rust-function-that-accepts-string-or-str.html) | [part 3](http://hermanradtke.com/2015/05/29/creating-a-rust-function-that-returns-string-or-str.html) - [Herman J. Radtke III][]
* [From &str to Cow](http://blog.jwilm.io/from-str-to-cow/) - Joe Wilm
* [How do I convert a &str to a String in Rust?](https://mgattozzi.com/how-do-i-str-string) - [Michael Gattozzi][]
* [Rust: str vs String](http://www.ameyalokare.com/rust/2017/10/12/rust-str-vs-String.html) - Ameya Lokare

### Syntax extensions

* :star: [Syntax extensions and regular expressions for Rust](http://blog.burntsushi.net/rust-regex-syntax-extensions/) - [Andrew Gallant][]

### Traits

* :star: [Abstraction without overhead: traits in Rust](http://blog.rust-lang.org/2015/05/11/traits.html) - [Aaron Turon][]
* [A series on trait objects part 1](https://huonw.github.io/blog/2015/01/peeking-inside-trait-objects) | [part 2](https://huonw.github.io/blog/2015/01/the-sized-trait) | [part 3](https://huonw.github.io/blog/2015/01/object-safety) | [part 4](https://huonw.github.io/blog/2015/05/where-self-meets-sized-revisiting-object-safety/) - [Huon Wilson][]
* [Rust traits for developer friendly libraries](https://benashford.github.io/blog/2015/05/24/rust-traits-for-developer-friendly-libraries/) - [Ben Ashford][]
* [Traits and trait objects](http://xania.org/201506/traits-and-trait-objects) - Matt Godbolt
* [Rust's Built-in Traits, the When, How & Why](https://llogiq.github.io/2015/07/30/traits.html) - [Llogiq][]
* [Where are you From::from](http://llogiq.github.io/2015/11/27/from-into.html) - [Llogiq][]
* :star: [Going down the rabbit hole with Rust traits](http://www.jonathanturner.org/2016/02/down-the-rabbit-hole-with-traits.html) - [Jonathan Turner][]
* [Gentle Intro to Type-level Recursion in Rust](https://beachape.com/blog/2017/03/12/gentle-intro-to-type-level-recursion-in-Rust-from-zero-to-frunk-hlist-sculpting/) - [Lloyd Chan][]

### Unsafe

* [Unsafe Rust: An Intro and Open Questions](http://cglab.ca/~abeinges/blah/rust-unsafe-intro/) - [Alexis Beingessner][]
* [Memory Leaks are Memory Safe](https://huonw.github.io/blog/2016/04/memory-leaks-are-memory-safe/) - [Huon Wilson][]
* :star: [On Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/29/on-reference-counting-and-leaks/) - [Niko Matsakis][]
* :star: [A Few More Remarks on Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/30/a-few-more-remarks-on-reference-counting-and-leaks/) - [Niko Matsakis][]
* [Pre-pooping Your Pants With Rust](http://cglab.ca/~abeinges/blah/everyone-poops/) - [Alexis Beingessner][]
* :star: [Unsafe Abstractions](http://smallcultfollowing.com/babysteps/blog/2016/05/23/unsafe-abstractions/) - [Niko Matsakis][]
* :star: [The "Tootsie Pop" Model for Unsafe Code](http://smallcultfollowing.com/babysteps/blog/2016/05/27/the-tootsie-pop-model-for-unsafe-code/) - [Niko Matsakis][]

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
* [Japanese](ja_JP.md)
* [Korean](ko_KR.md)
* [Russian](ru_RU.md)
* [Spanish](es_ES.md)
* [Turkish](tr_TR.md)

## People

This is the official [Rust Team](http://www.rust-lang.org/team.html) and [Servo Team](https://github.com/orgs/servo/people)

You search for a rustacean? [http://www.rustaceans.org/](http://www.rustaceans.org/)

You want to ask a something? [Users Forum](https://users.rust-lang.org/)

You want to meet them IRL? [Meetup groups](http://www.meetup.com/topics/rust/), [Community calendar](https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com), [Community talks list](https://github.com/rust-community/talks), [RustBridge](https://rustbridge.github.io/)

Go to rusty events? [RustFest](http://www.rustfest.eu/), [RustConf](http://rustconf.com/), [Rust Belt Rust](http://www.rust-belt-rust.com/)

You are looking for a job? [Rust Jobs](http://rustjobs.rs/)

Are you fast, friendly, and fearless? [Find something Rusty to work on!](https://www.rustaceans.org/findwork/starters)

You want to stay up to date? [The official blog](https://blog.rust-lang.org/), [This Week in Rust](https://this-week-in-rust.org/), [This Week in Rust Docs](http://guillaumegomez.github.io/this-week-in-rust-docs/), [The official reddit](https://www.reddit.com/r/rust/), [Rust Herald](https://herald.community.rs/)

### Famous Rustacean Bloggers

* [Aaron Turon][] - [blog](http://aturon.github.io/)
* [Andrew Gallant][] - [blog](http://blog.burntsushi.net/)
* [Andrew Hobden][] - [blog](https://hoverbear.org/tags/#rust)
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

* Workshop [slides and exercises](http://www.rust-tutorials.com/RustConf17/) from RustConf 2017.
* Niko Matsakis's [rust tutorializer](https://github.com/nikomatsakis/rust-tutorializer) framework
* Niko Matsakis's [ownership, borrowing, traits, structs, and threading tutorials](https://github.com/nikomatsakis/rust-tutorials-keynote), keynote files
* Niko Matsakis's [concurrency tutorial](https://github.com/nikomatsakis/concurrency-tutorial) from December 2015
* Niko Matsakis's [Mozlando Tutorial](http://smallcultfollowing.com/20151209/) includes slides and play.rust-lang.org demos
* Jim Blandy's [exercises](https://github.com/jimblandy/exercises)
* Dan Callahan's [Python Rust FFI](https://github.com/callahad/python-rust-ffi) examples
* Nick Cameron's [oopsla slides and exercises](http://ncameron.org/oopsla15.html)
* Florian Gilcher's [mailbox tutorial](https://github.com/skade/mailbox) takes Hello World to a whole new concurrent and networked level
* Carol Nichols' [Intro to Rust](https://github.com/carols10cents/intro-to-rust) that presents the guessing game and ownership in a similar manner as the book
* Jonathan Pallant's [Rust on the Raspberry Pi tutorial (using a the Sense HAT)](https://github.com/thejpster/pi-workshop-rs)

A few universities have had classes about Rust. Here are links to their public resources.

* University of Pennsylvania [CIS 198: Rust Programming](http://cis198-2016s.github.io/), Spring 2016, Rust 1.6. Slides linked from Schedule page.
* Northwestern University [EECS 3/495: Concurrent Programming in Rust](http://users.eecs.northwestern.edu/~jesse/course/eecs395rust-wi16/), Winter 2016, Rust 1.6. Slides linked from Schedule page.

<!-- Rustaceans -->
[Aaron Turon]: https://github.com/aturon
[Alex Crichton]: https://github.com/alexcrichton
[Alexis Beingessner]: https://github.com/Gankro
[Andrew Gallant]: https://github.com/BurntSushi
[Andrew Hobden]: https://github.com/Hoverbear
[Ben Ashford]: https://github.com/benashford
[Brian Anderson]: https://github.com/brson
[Carl Lerche]: https://github.com/carllerche
[Carol Nichols]: https://github.com/carols10cents
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
[Jeremiah Peschka]: https://github.com/peschkaj
[Jim Blandy]: https://github.com/jimblandy
[Jorge Aparicio]: https://github.com/japaric
[Josh Matthews]: https://github.com/jdm
[Jonathan Turner]: https://github.com/jonathandturner
[Llogiq]: https://github.com/llogiq
[Luqman Aden]: https://github.com/luqmana
[Lloyd Chan]: https://github.com/lloydmeta
[Huon Wilson]: https://github.com/huonw
[Manish Goregaokar]: https://github.com/Manishearth
[Michael Gattozzi]: https://github.com/mgattozzi
[Nick Cameron]: https://github.com/nrc
[Niko Matsakis]: https://github.com/nikomatsakis
[Pascal Hertleif]: https://github.com/killercup
[Patrick Walton]: https://github.com/pcwalton
[Seo Sanghyeon]: https://github.com/sanxiyn
[Simon Sapin]: https://github.com/SimonSapin
[Steve Donovan]: https://github.com/stevedonovan
[Steve Klabnik]: https://github.com/steveklabnik
[Steven Fackler]: https://github.com/sfackler
[Tetsuharu OHZEKI]: https://github.com/saneyuki
[Yehuda Katz]: https://github.com/wycats
[Dumindu Madunuwan]: https://github.com/dumindu

## Similar projects

* [Curated Resources to Learn Rust](https://hackr.io/tutorials/learn-rust) - Hackr.io
* [Rust Anthology Master List](https://github.com/brson/rust-anthology/blob/master/master-list.md) - [Brian Anderson][]
* [The Rust Community Blog](http://blog.community.rs/)

