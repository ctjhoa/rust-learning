# rust-learning [![Build Status](https://github.com/ctjhoa/rust-learning/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/ctjhoa/rust-learning/actions/workflows/main.yml)

A bunch of links to blog posts, articles, videos, etc for learning Rust. Feel free to submit a pull request if you have some links/resources to add. Also, I try to verify that the articles below have some real content (i.e. they aren't 2 paragraph long blog posts with little information) to ensure I'm not listing "fluff" pieces. If you have an idea for a better way to organize these links, please let me know.

## Introduction

*Do you want to be convinced that Rust is worth learning?* Let us show you the [True Nature of the Force](https://brson.github.io/fireflowers/).

The main documentation is always the best beginning, so if you haven't read it yet, start by reading the [Rust docs](https://www.rust-lang.org/en-US/documentation.html). You can also have the ebook versions of the doc [here](http://killercup.github.io/trpl-ebook/) and [here](https://github.com/lise-henry/books/).

### Tag meanings

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
  * [Async](#async)
  * [Closures](#closures)
  * [Documentation](#documentation)
  * [Enums](#enums)
  * [Errors](#errors)
  * [Iterators](#iterators)
  * [Lifetime](#lifetime)
  * [MIR](#mir)
  * [Modules](#modules)
  * [Option & Result](#option--result)
  * [Ownership / Concurrency](#ownership--concurrency)
  * [Privacy](#privacy)
  * [Strings](#strings)
  * [Syntax extensions](#syntax-extensions)
  * [Traits](#traits)
  * [Unsafe](#unsafe)
* [Playground](#playground)
* [Locale links](#locale-links)
* [People](#people)
  * [Fearless Rust Bloggers](#fearless-rust-bloggers)
* [Tutorials & Workshop Materials](#tutorials--workshop-materials)
* [Similar projects](#similar-projects)

## Books

* :star: [The Rust Programming Language](https://doc.rust-lang.org/stable/book/) - [repo](https://github.com/rust-lang/book)
* :star: [The Rust Reference](https://doc.rust-lang.org/stable/reference/) - [repo](https://github.com/rust-lang/reference)
* :star: [The Rustonomicon - The Dark Arts of Advanced and Unsafe Rust Programming](https://doc.rust-lang.org/stable/nomicon/) - [repo](https://github.com/rust-lang/nomicon)
* :star: [The Unstable Book](https://doc.rust-lang.org/stable/unstable-book/) - [repo](https://github.com/rust-lang/rust/tree/master/src/doc/unstable-book)
* :star: [The Rust Edition Guide](https://doc.rust-lang.org/edition-guide/) - [repo](https://github.com/rust-lang/edition-guide)
* :star: [The Rust Async Book](https://rust-lang.github.io/async-book/) - [repo](https://github.com/rust-lang/async-book)
* :star: [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) - [repo](https://github.com/rust-lang-nursery/rust-cookbook)
* :star: [Why Rust?](https://www.oreilly.com/content/why-rust/) - [Jim Blandy][]
* :star: [The Embedded Rust Book](https://rust-embedded.github.io/book/intro/index.html) - [repo](https://github.com/rust-embedded/book) - Rust Embedded WG
* :star: [The Cargo Book](https://doc.rust-lang.org/stable/cargo/) - [repo](https://github.com/rust-lang/cargo/tree/master/src/doc)
* [Rust-101](https://www.ralfj.de/projects/rust-101/main.html) - Ralf Jung
* [Rust Essentials](https://www.packtpub.com/application-development/rust-essentials-second-edition) -  Ivo Balbaert
* [Programming Rust](http://shop.oreilly.com/product/0636920040385.do) - [Jim Blandy][], Jason Orendorff
* [Mastering Rust - Second Edition](https://www.packtpub.com/application-development/mastering-rust-second-edition) - Rahul Sharma & Vesa Kaihlavirta
* :soon: [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - [repo](https://github.com/natemara/refactoring-to-rust) - Nate Mara
* :star: [Rust Anthology](https://github.com/brson/rust-anthology) - [Brian Anderson][]
* [Rust in Action](https://www.manning.com/books/rust-in-action) - [repo](https://github.com/rust-in-action/code) - [Tim McNamara][]
* [Zero To Production In Rust](https://zero2prod.com) - [repo](https://github.com/LukeMathWalker/zero-to-production) - [Luca Palmieri][]
* [Network Programming in Rust](https://www.packtpub.com/application-development/network-programming-rust) - Abhishek Chanda
* [Learning Rust](https://www.packtpub.com/application-development/learning-rust) -  Paul Johnson, Vesa Kaihlavirta
* [Rust Cookbook](https://www.packtpub.com/application-development/rust-cookbook) -  Vigneshwer Dhinakaran
* [Learning Rust](https://learning-rust.github.io/) - [Dumindu Madunuwan][]
* [A Gentle Introduction To Rust](http://stevedonovan.github.io/rust-gentle-intro/readme.html) - [Steve Donovan][]
* [Step Ahead with Rust](https://www.amazon.com/dp/0999361805/) - Jonathan Creekmore
* :star: [Rust Programming By Example](https://www.amazon.com/dp/1788390636) - Guillaume Gomez and Antoni Boucher
* [Beginning Rust - From Novice to Professional](https://www.apress.com/us/book/9781484234679) - Carlo Milanesi
* [Hands-On Concurrency with Rust](https://www.amazon.com/dp/1788399978) - Brian Troutwine
* [Hands-On Functional Programming in Rust](https://www.amazon.com/dp/1788839358) - Andrew Johnson
* [Hands-On Rust Effective Learning through 2D Game Development and Play](https://pragprog.com/titles/hwrust/hands-on-rust) - Herbert Wolverson
* [Hands-On Microservices with Rust](https://www.packtpub.com/web-development/hands-microservices-rust) - Denis Kolodin
* [Hands-On Data Structures and Algorithms with Rust](https://www.packtpub.com/application-development/hands-data-structures-and-algorithms-rust) - Claus Matzinger
* [Rust Standard Library Cookbook](https://www.amazon.com/Rust-Standard-Library-Cookbook-leverage/dp/1788623924) - Daniel Durante, Jan Nils Ferner
* [Rust Quick Start Guide](https://www.amazon.com/Rust-Quick-Start-Guide-programming/dp/1789616700) - Daniel Arbuckle
* [Rust High Performance](https://www.amazon.com/Rust-High-Performance-performance-applications/dp/178839948X) - Iban Eguia Moraza
* [Programming WebAssembly with Rust](https://pragprog.com/titles/khrust/programming-webassembly-with-rust/) - Kevin Hoffman
* [Hands-On Microservices with Rust 2018: How To Build Scalable and Reliable RESTful Microservices](https://www.amazon.co.uk/Hands-Microservices-Rust-2018-Scalable/dp/1789342759/ref=sr_1_6?s=books&ie=UTF8&qid=1545340800&sr=1-6&keywords=rust) - Denis Kolodin
* [Hands-On Data Structures and Algorithms with Rust](https://www.packtpub.com/application-development/hands-data-structures-and-algorithms-rust) - Claus Matzinger
* [The Complete Rust Programming Reference Guide: Design, develop, and deploy effective software systems using the advanced constructs of Rust](https://www.amazon.com/Complete-Rust-Programming-Reference-Guide/dp/1838828109) - - Vesa Kaihlavirta, Rahul Sharma, Claus Matzinger
* [Easy Rust](https://github.com/Dhghomon/easy_rust) - David MacLeod
* [Rust Web Development](https://www.manning.com/books/rust-web-development) - [repo](https://github.com/Rust-Web-Development/code) - Bastian Gruber
* [The Little Book of Rust Books](https://lborb.github.io/book/) - [repo](https://github.com/lborb/book)
* [Rust Servers, Services, and Apps](https://www.manning.com/books/rust-servers-services-and-apps) - Prabhu Eshwarla
* [Code Like a Pro in Rust](https://www.manning.com/books/code-like-a-pro-in-rust) - Brenden Matthews
* [Rust for Rustaceans](https://nostarch.com/rust-rustaceans) - Jon Gjengset
* [Rust From the Ground Up](https://rftgu.rs/) - Matthew Provost
* [Comprehensive Rust](https://google.github.io/comprehensive-rust/) - Google
* [Rust Atomics and Locks](https://learning.oreilly.com/library/view/-/9781098119430/) - Mara Bos
* [Command-Line Rust](https://www.oreilly.com/library/view/command-line-rust/9781098109424/) - Ken Youens-Clark
* [High Assurance Rust: Developing Secure and Robust Software](https://highassurance.rs/) - Tiemoko Ballo

## Videos

### Playlists

* :star: [Rust and the Future of Systems Programming](https://www.youtube.com/playlist?list=PLo3w8EB99pqJ74XIGe72c9hBZWz9Y16cY) - Mozilla
* [RustFest Zürich 2017](https://www.youtube.com/watch?v=jywiVWKm1TI&list=PL85XCvVPmGQj9mqbJizw-zi-EhcpS5jTP)
* [ABitWiseGuy Tutorials](https://www.youtube.com/watch?v=y-ks-_VDkiA&list=PL0Fqs05rod8D80WKBCeT326CT8vcAm_N9) - ABitWiseGuy
* [dcode Tutorials](https://www.youtube.com/watch?v=vOMJlQ5B-M0&list=PLVvjrrRCBy2JSHf9tGxGKJ-bYAN_uDCUL) - dcode
* [maxday_coding](https://www.youtube.com/watch?v=Idys2BAmqIU&list=PLCqkr2gc0bmZZOvjXC6BJGTGEuah_1Hbi) - ASMR Live Coding
* [Tensor Programming Tutorials](https://www.youtube.com/watch?v=EYqceb2AnkU&list=PLJbE2Yu2zumDF6BX6_RdPisRVHgzV02NW) - Tensor Programming
* [Hello Rust!](https://www.youtube.com/channel/UCZ_EWaQZCZuGGfnuqUoHujw) - Matthias Endler
* [YouCodeThings](https://www.youtube.com/channel/UC0yCXVwW6FdDQGYA-3OWXxw/) - Andrew Jakubowicz
* :star: :soon: [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion) - Video course by [Carol Nichols][] and Jake Goulding
* [Learn Rust in 7 Days](https://www.packtpub.com/application-development/learn-rust-7-days-video) - Matthew Stoodley
* [Rust Tutorial](https://www.youtube.com/watch?v=Az3jBd4xdF4&list=PLLqEtX6ql2EyPAZ1M2_C0GgVd4A-_L4_5) - Doug Milford
* [Rust](https://www.youtube.com/watch?v=bR4nGWmfzTk&list=PLVhhUNGAUIQScqB26DdUq4n1Y2n3auM7X) - Crazcalm's Tech Stack
* [Rust Advent of Code 2019](https://www.youtube.com/playlist?list=PLQXBtq4j4Ozkx3r4eoMstdkkOG98qpBfg) - Brian Myers
* [The Rust Programming Language | Tutorials](https://www.youtube.com/playlist?list=PLK_g1a_cAfaaAO6io1Tluy7EZXhAAK1lC) - danlogs
* [Ryan Levick's Rust Stream](https://www.youtube.com/channel/UCpeX4D-ArTrsqvhLapAHprQ/videos) - Ryan Levick
* [Crust of Rust](https://www.youtube.com/playlist?list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa) - Jon Gjengset
* [ULTIMATE Rust Lang Tutorial!](https://www.youtube.com/watch?v=OX9HJsJUDxA&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8) - Let's Get Rusty
* [Overview of the Rust Programming Language](https://www.youtube.com/watch?v=gesNaLkUJeA&list=PLP2yfE2-FXdQmXLvrQ5QN64enbF_KCYQW) - [Jonathan Turner][]
* [Manning Publications Rust channel](https://www.youtube.com/c/ManningPublications/search?query=rust) - Manning Publications
* [Introduction to Programming with Rust](https://www.youtube.com/playlist?list=PLbtjxiXev6lpd331MW2dB7UgSIovgv169) - Rhymu's Videos
* [Rust Linz](https://www.youtube.com/playlist?list=PL85XCvVPmGQgL3lqQD5ivLNLfdAdxbE_u) - A Rust Meetup aimed at beginners
* [Rust Programming Tutorial 🦀](https://www.youtube.com/playlist?list=PLDbRgZ0OOEpUkWDGqp91ODn0dk7LPBAUL) - Rust fundamentals YouTube playlist by [Trevor Sullivan](https://docs.opensrc.dev)

### Presentations

* 2021-06-25 - [How to learn Rust](https://youtu.be/sDtQaO5_SOw) - [Tim McNamara][]
* 2021-06-01 - [A Firehose of Rust, for busy people who know some C++](https://www.youtube.com/watch?v=IPmRDS0OSxM) - Jack O'Connor
* 2020-09-21 - [live@Manning Rust Conference](https://www.youtube.com/watch?v=9nINNurVqz8) - [Carol Nichols][], [Tim McNamara][], Maciej Hirsz, Olivia Ifrim, Nell Shamrell-Harrington, Pierre Krieger, Richard Walters, Chris Griffing, Lachezar Lechev, Michael Hausenblas
* 2018-08-17 - [Using Rust For Game Development](https://www.youtube.com/watch?v=aKLntZcp27M) - Catherine West
* 2017-06-20 - :star: [Rust: Putting Ownership to Use](https://www.youtube.com/watch?v=wXoY91w4Agk) - [Niko Matsakis][]
* 2017-01-20 - [Rust 101](https://www.youtube.com/watch?v=FMqydRampuo) - E. Dunham
* 2016-09-28 - [Mozilla's Rust and why we love it](https://www.youtube.com/watch?v=LuNhkRxP2E4) - Cambridge Consultants
* 2016-09-25 - :star: [into_rust() - Screencasts for learning rust!](http://intorust.com/) - [Niko Matsakis][]
* 2016-08-28 - :star: [Rust: Safe and Scalable Systems Programming](https://www.youtube.com/watch?v=GbWECt0M3CI) - [Alex Crichton][]
* 2016-06-21 - :star: [The History of Rust](https://www.youtube.com/watch?v=79PSagCD_AY) - [Steve Klabnik][]
* 2015-08-01 - :star: [RustCamp 2015](https://www.youtube.com/watch?v=0qIAk5sTwEo&list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t)
* 2015-06-22 - [LambdaConf 2015 - In Rust We Trust](https://www.youtube.com/watch?v=-dxqbhLIgdM) - Alex Burkhart
* 2015-06-13 - :star: [What Is Rust?](http://www.infoq.com/presentations/rust-gc) - [Yehuda Katz][]
* 2015-04-11 - [My Python's a little Rust-y](https://www.youtube.com/watch?v=3CwJ0MH-4MA) - [Dan Callahan][]
* 2015-03-12 - :star: [Stanford Seminar](https://www.youtube.com/watch?v=O5vzLKg7y-k) - [Aaron Turon][]

## Podcasts

* [Moves and Borrowing In Rust With Jim Blandy](https://corecursive.com/016-moves-and-borrowing-in-rust-with-jim-blandy/) - Adam Bell
* [New Rustacean](https://pca.st/DG0A) - [Chris Krycho][]
* [The Request for Explanation Podcast: A weekly discussion of Rust RFCs](https://request-for-explanation.github.io/podcast/) - [Manish Goregaokar][]
* [Rust And Bitter C++ Developers With Jim Blandy](https://corecursive.com/013-rust-and-bitter-c-developers-with-jim-blandy/) - Adam Bell
* [AreWePodcastYet](https://soundcloud.com/arewepodcastyet)
* [Rustacean Station](https://rustacean-station.org/)

## Rust in practice

* :star: [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/) - [Jorge Aparicio][] and [Steve Klabnik][] - [repo](https://github.com/rust-lang/rust-by-example)
* [rosettacode](https://github.com/Hoverbear/rust-rosetta) - [Ana Hoverbear][]
* [Why your first FizzBuzz implementation may not work](http://chrismorgan.info/blog/rust-fizzbuzz.html) - [Chris Morgan][]
* :star: [An annotation of the Rust standard library](https://github.com/brson/annotated-std-rs) - [Brian Anderson][]
* [ProjectEulerRust](https://github.com/gifnksm/ProjectEulerRust) - gifnksm
* [Advent of Code](https://github.com/LD250/adventofcode_rust) - Denys Levchenko
* [Rust in Detail: Writing Scalable Chat Service from Scratch](https://nbaksalyar.github.io/) - Nikita Baksalyar
* :star: [rustlings: small rust exercises](https://github.com/carols10cents/rustlings) - [Carol Nichols][]
* [Learning Rust With Entirely Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/) - [Alexis Beingessner][]
* :star: [Let's build a browser engine!](http://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html) - Matt Brubeck
* [Understanding Over Guesswork](http://hoverbear.org/2015/09/12/understand-over-guesswork/) - [Ana Hoverbear][]
* [Writing an OS in Rust 1st edition](http://os.phil-opp.com/) [2nd edition](https://os.phil-opp.com/second-edition/) - Philipp Oppermann
* [Creating Nintendo 64 emulator from scratch in Rust!](https://www.youtube.com/playlist?list=PL-sXmdrqqYYcznDg4xwAJWQgNL2gRray2) - Jake Taylor
* [The Many Kinds of Code Reuse in Rust](http://cglab.ca/~abeinges/blah/rust-reuse-and-recycle/) - [Alexis Beingessner][]
* [Make a Lisp](https://github.com/kanaka/mal) - Joel Martin
* :star: [Modeling Graphs in Rust Using Vector Indices](http://smallcultfollowing.com/babysteps/blog/2015/04/06/modeling-graphs-in-rust-using-vector-indices/) - [Niko Matsakis][]
* [24 days of Rust series](https://siciarz.net/tag/24%20days%20of%20rust/) - Zbigniew Siciarz
* :star: [Rust Cookbook](https://github.com/brson/rust-cookbook)
* :star: [Rust and CSV Parsing](http://blog.burntsushi.net/csv/) - [Andrew Gallant][]
* [Algorithm Cookbook in Rust](https://github.com/EbTech/rust-algorithms) - Aram Ebtekar
* :star: [stdx - The missing batteries of Rust](https://github.com/brson/stdx) - [Brian Anderson][]
* [Rust - exercism.org](https://exercism.org/tracks/rust)
* [Building a DNS server in Rust](https://github.com/EmilHernvall/dnsguide) - Emil Hernvall
* [Rust Crash Course](https://www.snoyman.com/feed/rust-crash-course) - Michael Snoyman
* [Web browser from scratch in Rust](https://joshondesign.com/tags/browser) - Josh Marinacci
* [Tour of Rust](https://tourofrust.com/) - Richard Anaya
* [PNGme: An Intermediate Rust Project](https://jrdngr.github.io/pngme_book/) - Jordan Grace
* [Create Your Own Programming Language with Rust](https://createlang.rs/) - Ehsan M. Kermani
* :star: [Command Line Applications in Rust](https://rust-cli.github.io/book/) - Rust CLI working
* [Writing a file system from scratch in Rust](https://blog.carlosgaldino.com/writing-a-file-system-from-scratch-in-rust.html) - Carlos Galdino
* [Hecto: Build your own text editor in Rust](https://www.flenker.blog/hecto/) - Philipp Flenker
* [Rust sokoban](https://sokoban.iolivia.me/) - Olivia Ifrim
* [Rust Gym](https://github.com/warycat/rustgym) - Yinchu Xia
* :star: [Rust Quiz](https://dtolnay.github.io/rust-quiz) - [David Tolnay][]
* [Blessed - An unofficial guide to the Rust ecosystem](https://blessed.rs/crates) - Nico Burns
* [Build a Lua Interpreter in Rust](https://wubingzheng.github.io/build-lua-in-rust/en/) - Wu Bingzheng
* [Object Soup is Made of Indexes](https://jacko.io/object_soup.html) - Jack O'Connor
* [Implementing a BitTorrent client in Rust](https://www.youtube.com/watch?v=jf_ddGnum_4&t=135s&ab_channel=JonGjengset) - Jon Gjengset
* [Rust on Serverless](https://www.youtube.com/watch?v=i6FKvK5JQ8o&list=PLCOG9xkUD90KQ1IPQT_m1NbPRXXRFb63s) - YouTube playlist exploring the use of Rust to build serverless applications by [James Eastham](https://jameseastham.co.uk)

## Best Practices/Style Guides

* :star: [Rust Design Patterns](https://github.com/nrc/patterns) - [Nick Cameron][]
* :star: [Error Handling in Rust](http://blog.burntsushi.net/rust-error-handling/) - [Andrew Gallant][]
* :star: [Rust API guidelines](https://github.com/rust-lang/api-guidelines) - [Brian Anderson][]
* [Design Patterns in Rust](https://github.com/fadeevab/design-patterns-rust) - [Alexander Fadeev][]
* [Reading Rust Function Signatures](http://hoverbear.org/2015/07/10/reading-rust-function-signatures/) - [Ana Hoverbear][]
* [Good Practices for Writing Rust Libraries](https://pascalhertleif.de/artikel/good-practices-for-writing-rust-libraries/) - [Pascal Hertleif][]
* [Rustic Bits](https://llogiq.github.io/2016/02/11/rustic.html) - [Llogiq][]
* [Pretty State Machine Patterns in Rust](https://hoverbear.org/2016/10/12/rust-state-machine-pattern/) - [Ana Hoverbear][]
* [Elegant Library APIs in Rust](https://scribbles.pascalhertleif.de/elegant-apis-in-rust.html) - [Pascal Hertleif][]
* [Rust Performance Pitfalls](https://llogiq.github.io/2017/06/01/perf-pitfalls.html) - [Llogiq][]
* [How to write CRaP Rust code](https://blog.logrocket.com/how-to-write-crap-rust-code/) - [Llogiq][]
* [The Rust Performance Book](https://github.com/nnethercote/perf-book) - Nicholas Nethercote
* [The Typestate Pattern in Rust](http://cliffle.com/blog/rust-typestate/) - Cliff L. Biffle

## Cheat sheets

* :star: [Syntax Index](https://doc.rust-lang.org/book/syntax-index.html)
* [Rust Iterator Cheat Sheet](https://danielkeep.github.io/itercheat_baked.html) - [Daniel Keep][]
* [Rust String Conversions Cheat Sheet](https://docs.google.com/spreadsheets/d/19vSPL6z2d50JlyzwxariaYD6EU2QQUQqIDOGbiGQC7Y/pubhtml?gid=0&single=true) - GavinB
* [Rustic Symmetries](https://github.com/kmcallister/rustic-symmetries/blob/master/README.md#rustic-symmetries) - kmc
* [Rust Container Cheat Sheet](https://docs.google.com/presentation/d/1q-c7UAyrUlM-eZyTo1pd8SZ0qwA_wYxmPZVOQkoDmH4/edit?usp=sharing) - Raph Levien
* [Graphical depiction of ownership and borrowing in Rust](https://rufflewind.com/img/rust-move-copy-borrow.png) - Phil Ruffwind
* [Lifetime Reference](https://charlesetc.inclouds.space/lifetime-reference/) - Charles
* [Phaiax's Rust Cheatsheet](http://phaiax.github.io/rust-cheatsheet/) - Phaiax
* [Rust Language Cheat Sheet](https://cheats.rs/) - Ralf Biedert
* [Rust cheat sheet (beginner-oriented)](https://www.breakdown-notes.com/make/load/rust_cs_canvas/true)
* [A type-based Rust cheatsheet](https://upsuper.github.io/rust-cheatsheet/) - Xidorn Quan

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
* [Rust your ARM microcontroller!](http://blog.japaric.io/quickstart/) - [Jorge Aparicio][]
* [Cross-compiling Rust for the Raspberry Pi on macOS](https://akappel.github.io/2017/11/07/rpi-crosstool.html) - Adrian Kappel
* [rust-on-mobile](https://github.com/mtak-/rust-on-mobile) - mtak-
* [Compile Time Feature Flags in Rust](https://www.worthe-it.co.za/programming/2018/11/18/compile-time-feature-flags-in-rust.html) - Justin Worthe
* [Rust on iOS](https://medium.com/visly/rust-on-ios-39f799b3c1dd) - Emil Sjölander

## FFI

* 2017-11-22 - [Writing fast and safe native Node.js modules with Rust](https://blog.risingstack.com/node-js-native-modules-with-rust/) - Peter Czibik
* 2017-09-21 - [Building and Deploying a Rust library on Android](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-21-rust-on-android.html) - Emily Toop
* 2017-09-06 - [Building and Deploying a Rust library on iOS](https://mozilla.github.io/firefox-browser-architecture/experiments/2017-09-06-rust-on-ios.html) - Emily Toop
* 2020-09-08 - [I C and .so does Rust](https://prateeknischal.github.io/posts/i-c-and-so-does-rust/) - prateeknischal
* [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/?updated=2015-11-08) - Jake Goulding
* [The Rust FFI Guide - using unsafe for fun and profit](https://michael-f-bryan.github.io/rust-ffi-guide/) - Michael-F-Brya

## CI / Testing

* [Helping Travis catch the rustc train part 1](https://huonw.github.io/blog/2015/04/helping-travis-catch-the-rustc-train/) | [part 2](https://huonw.github.io/blog/2015/05/travis-on-the-train-part-2/) - [Huon Wilson][]
* [Rust, Travis, and Github Pages](http://hoverbear.org/2015/03/07/rust-travis-github-pages/) - [Ana Hoverbear][]
* [Shave Some Time From Your Travis Builds](https://llogiq.github.io/2016/07/05/travis.html) - [Llogiq][]
* [How to collect test coverages for a rust project](https://users.rust-lang.org/t/tutorial-how-to-collect-test-coverages-for-rust-project/650) - lifthrasiir
* [Rust Performance Testing on Travis CI](https://beachape.com/blog/2016/11/02/rust-performance-testing-on-travis-ci/) - Lloyd
* [Ensuring Beautiful Commits with rustfmt and Travis-CI](http://kneit.in/2016/11/26/rustfmt-in-travisci.html) - Kyle Kneitinger
* [Great Rust CI](https://dev.to/cad97/great-rust-ci-1fk6) - Christopher Durham
* [Rust Fuzz Book](https://rust-fuzz.github.io/book/)
* [Rust for JavaScript Developers: An Overview of Testing](https://www.shuttle.rs/blog/2023/11/08/testing-in-rust) - Joshua Mo

## Debug / Profiling

* [Debugging a segfault in my Rust program](https://jvns.ca/blog/2017/12/23/segfault-debugging/) - Julia Evans
* [Compiler Explorer - See Rust code as assembly](https://rust.godbolt.org/)
* [Profiling Rust applications on Linux](http://llogiq.github.io/2015/07/15/profiling.html) - [Llogiq][]

## Are we ... yet?

* [Are we web yet?](http://www.arewewebyet.org/)
* [Are we (I)DE yet?](https://areweideyet.com/)
* [Are we game yet?](http://arewegameyet.com/)
* [Are we learning yet?](http://www.arewelearningyet.com/)
* [Are we async yet?](https://areweasyncyet.rs/)
* [Not-Yet-Awesome Rust](https://github.com/ErichDonGubler/not-yet-awesome-rust)
* [Are we GUI yet?](http://areweguiyet.com/)

## Comparison with Other Languages

* [Rust::from(lang)](https://github.com/mgattozzi/rust-from-lang) - [Michael Gattozzi][]
* Others:

| Languages       | Links                                    |
| --------------- | ---------------------------------------- |
| C#              | <ul><li>[Exploring Rust (from C#)](http://nblumhardt.com/2016/03/exploring-rust/) - Nicholas Blumhardt</li></ul> |
| C/C++           | <ul><li>[Rust For Systems Programmers](https://github.com/nrc/r4cppp) & [Rust for C++ Programmers](https://www.gitbook.com/book/aminb/rust-for-c/details) - [Nick Cameron][]</li><li>[I used to use pointers - now what?](https://github.com/diwic/reffers-rs/blob/master/docs/Pointers.md) - diwic</li><li>[Comparing parallel Rust and C++](https://parallel-rust-cpp.github.io/) - matiaslindgren</li><li>[Zero cost abstractions: Rust vs C++](https://www.rottedfrog.co.uk/?p=24) - rottedfrog</li><li>[A Firehose of Rust, for busy people who know some C++](https://www.youtube.com/watch?v=IPmRDS0OSxM) - Jack O'Connor</li><li>[Unsafe Rust is not C](https://www.youtube.com/watch?v=DG-VLezRkYQ) - Jack O'Connor</li></ul> |
| Clojure         | <ul><li>[Rust for Clojurists](https://gist.github.com/oakes/4af1023b6c5162c6f8f0) - Zach Oakes</li></ul> |
| Go | <ul><li>[Rust vs Go](https://bitfieldconsulting.com/golang/rust-vs-go) - John Arundel</li><li>[Rust vs. Go](http://julio.meroh.net/2018/07/rust-vs-go.html) - Julio Merino</li></ul> |
| Java/Scala            | <ul><li>[Comparing Rust and Java](https://llogiq.github.io/2016/02/28/java-rust.html) - [Llogiq][]</li><li>[A light comparison between Rust and Java generics and type system features.](https://gist.github.com/Kimundi/8391398) - Marvin Löbel</li><li>[Rust: A Scala Engineer's Perspective](https://beachape.com/blog/2017/05/24/rust-from-scala/) - Lloyd </li><li>[Rust for professionals](https://overexact.com/rust-for-professionals/) - Pascal</li></ul> |
| JavaScript      | <ul><li>[Rust's Ownership model for JavaScript developers](http://blog.thoughtram.io/rust/2015/05/11/rusts-ownership-model-for-javascript-developers.html) - [Christoph Burgdorf][]</li><li>[Rust for Node developers](https://github.com/Mercateo/rust-for-node-developers) - Donald Pipowitch</li><li>[Rust for professionals](https://overexact.com/rust-for-professionals/) - Pascal</li></ul> |
| Nim             | <ul><li>[A Quick Comparison of Nim vs. Rust](https://arthurtw.github.io/2015/01/12/quick-comparison-nim-vs-rust.html) - Arthur Liao</li></ul> |
| Nodejs          | <ul><li>[Rust for Node developers](https://github.com/Mercateo/rust-for-node-developers) - Donald Pipowitch</li></ul> |
| OCaml / Haskell | <ul><li>[Rust for functional programmers](http://science.raphael.poss.name/rust-for-functional-programmers.html)</li></ul> |
| Python          | <ul><li>[Rust for Python Programmers](http://lucumr.pocoo.org/2015/5/27/rust-for-pythonistas/) - Armin Ronacher</li><li>[py2rs](https://github.com/rochacbruno/py2rs) - Bruno Rocha</li></ul> |
| Ruby            | <ul><li>[Rust for Rubyists](https://github.com/steveklabnik/rust_for_rubyists) - [Steve Klabnik][]</li></ul> |
| Swift           | <ul><li>[A Swift guide to Rust](http://faq.sealedabstract.com/rust/) - sealedabstract</li><li>[Rust and Swift](http://www.chriskrycho.com/rust-and-swift.html) - [Chris Krycho][]</li></ul> |
| Erlang           | <ul><li>[A Comparison between erlang and rust starting from language semantics to runtime features, performance etc..](https://www.infoq.com/articles/rust-erlang-comparison) - Krishna Kumar Thokala</li></ul> |

## Applications / Libraries / Tools

See repos [kud1ing/awesome-rust](https://github.com/kud1ing/awesome-rust) & [awesomo
/rust](https://github.com/lk-geimfari/awesomo/blob/master/languages/RUST.md)

## Language stuff

Can I use feature X? [caniuse.rs - Rust feature search](https://caniuse.rs/)

### Async

* [Futures Explained in 200 Lines of Rust](https://web.archive.org/web/20230324130904/https://cfsamson.github.io/books-futures-explained/) - Carl Fredrik Samson
* [Introduction to Async Rust and a High-level Overview of Tokio’s Architecture](https://moslehian.com/posts/2023/1-intro-async-rust-tokio/) - Arash Sal Moslehian
* [Async Rust in Three Parts](https://jacko.io/async_intro.html) - Jack O'Connor

### Closures

* [Finding Closure in Rust](https://huonw.github.io/blog/2015/05/finding-closure-in-rust/) - [Huon Wilson][]
* [Defaulting to Thread-Safety: Closures and Concurrency](https://huonw.github.io/blog/2015/05/defaulting-to-thread-safety/) - [Huon Wilson][]
* [How to pass a closure into a trait object](http://camjackson.net/post/rust-lang-how-to-pass-a-closure-into-a-trait-object) - Cam Jackson
* [Practical differences between Rust closures and functions](https://ricardomartins.cc/2015/10/12/practical_differences_between_rust_closures_and_functions) - Ricardo Martins
* :star: [How Rust Achieves Thread Safety](https://manishearth.github.io/blog/2015/05/30/how-rust-achieves-thread-safety/) - [Manish Goregaokar][]
* [Understanding Closures in Rust](https://medium.com/swlh/understanding-closures-in-rust-21f286ed1759) - Andrew Pritchard
* [Why Rust Closures are (Somewhat) Hard](https://stevedonovan.github.io/rustifications/2018/08/18/rust-closures-are-hard.html) - [Steve Donovan][]

### Documentation

* :star: [Writing Documentation in Rust](https://www.facility9.com/2016/05/10/writing-documentation-in-rust/) - [Jeremiah Peschka][]
* [Keeping Rust projects' README.md code examples up-to-date](https://blog.guillaume-gomez.fr/articles/2019-04-13+Keeping+Rust+projects%27+README.md+code+examples+up-to-date) - Guillaume Gomez
* [Guide on how to write documentation for a Rust crate](https://blog.guillaume-gomez.fr/articles/2020-03-11+Guide+on+how+to+write+documentation+for+a+Rust+crate) - Guillaume Gomez

### Enums

* :star: [Virtual Structs part 1](http://smallcultfollowing.com/babysteps/blog/2015/05/05/where-rusts-enum-shines/) | [part 2](http://smallcultfollowing.com/babysteps/blog/2015/05/29/classes-strike-back/) | [part 3](http://smallcultfollowing.com/babysteps/blog/2015/08/20/virtual-structs-part-3-bringing-enums-and-structs-together/) - [Niko Matsakis][]

### Errors

* :star: [Error Handling in Rust](https://nrc.github.io/error-docs/) - [Nick Cameron][]
* :star: [Error Handling in Rust](https://blog.burntsushi.net/rust-error-handling/) - [Andrew Gallant][]
* [Beginner's guide to Error Handling in Rust](http://www.sheshbabu.com/posts/rust-error-handling/) - Sheshbabu Chinnakonda
* [Rust error handling](https://www.unwoundstack.com/blog/rust-error-handling.html) - sp1ff
* [Rust: Structuring and handling errors in 2020](https://nick.groenen.me/posts/rust-error-handling/) - Nick Groenen
* [Wrapping errors in Rust](https://edgarluque.com/blog/wrapping-errors-in-rust/) - Edgar Luque
* [Designing error types in Rust](https://mmapped.blog/posts/12-rust-error-handling.html) - Roman Kashitsyn

### Iterators

* [A Journey into Iterators](http://hoverbear.org/2015/05/02/a-journey-into-iterators/) - [Ana Hoverbear][]
* [Effectively Using Iterators In Rust](http://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html) - [Herman J. Radtke III][]
* [for loops in Rust](http://xion.io/post/code/rust-for-loop.html) - Karol Kuczmarski
* [Iteration patterns for Result & Option](http://xion.io/post/code/rust-iter-patterns.html) - Karol Kuczmarski
* [Little tour of multiple iterators implementation in Rust](https://blog.guillaume-gomez.fr/articles/2017-03-09+Little+tour+of+multiple+iterators+implementation+in+Rust) - Guillaume Gomez
* [rust-iterators](https://github.com/rustomax/rust-iterators/) - Max Skybin

### Lifetime

* :star: [Where Rust Really Shines](https://manishearth.github.io/blog/2015/05/03/where-rust-really-shines/) - [Manish Goregaokar][]
* [Understanding Lifetime in Rust part 1](https://mobiarch.wordpress.com/2015/06/29/understanding-lifetime-in-rust-part-i/) | [part 2](https://mobiarch.wordpress.com/2015/07/08/understanding-lifetime-in-rust-part-ii-3/) - Bibhas Bhattacharya
* [Rust Lifetimes](https://charlesetc.inclouds.space/rust-lifetimes/) - Charles
* [The Power of Lifetimes](http://pling.jondgoodwin.com/post/lifetimes/) - Jonathan Goodwin
* [Understanding Rust Lifetimes](https://medium.com/nearprotocol/understanding-rust-lifetimes-e813bcd405fa) - Maksym Zavershynskyi
* [Common Rust Lifetime Misconceptions](https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md) - kirill
* [LifetimeKata](https://github.com/tfpk/lifetimekata) - Tom Kunc

### Macros

* [A Practical Intro to Macros in Rust 1.0](https://danielkeep.github.io/practical-intro-to-macros.html) - [Daniel Keep][]
* [The Little Book of Rust Macros](https://veykril.github.io/tlborm/) - Lukas Wirth
* :star: [Macros in Rust part 1](http://www.ncameron.org/blog/macros-in-rust-pt1/) | [part 2](http://www.ncameron.org/blog/macros-in-rust-pt2/) | [part 3](http://ncameron.org/blog/macros-in-rust-pt3/) | [part 4](http://ncameron.org/blog/macros-in-rust-pt4/) - [Nick Cameron][]
* [Writing complex macros in Rust: Reverse Polish Notation](https://rreverser.com/writing-complex-macros-in-rust/) - Ingvar Stepanyan
* :star: [Procedural Macros in Rust 2018](https://blog.rust-lang.org/2018/12/21/Procedural-Macros-in-Rust-2018.html) - [Alex Crichton][]
* [Creating Macros in Rust](https://hub.packtpub.com/creating-macros-in-rust-tutorial/) - Aaron Lazar
* [Rust Latam: procedural macros workshop](https://github.com/dtolnay/proc-macro-workshop) - David Tolnay
* [MacroKata](https://github.com/tfpk/macrokata) - Tom Kunc

### MIR

* :star: [Introducing MIR](http://blog.rust-lang.org/2016/04/19/MIR.html) - [Niko Matsakis][]

### Modules

* [Rust Module Essentials ](https://dev.to/hertz4/rust-module-essentials-12oi) - Sam Pagenkopf
* [How I Organize Large Rust Programs](https://rodarmor.com/blog/tour-de-just/) - Casey Rodarmor
* [Clear explanation of Rust’s module system](http://www.sheshbabu.com/posts/rust-module-system/) - Sheshbabu Chinnakonda

### Option & Result

* [Option Type part 1](https://8thlight.com/insights/the-option-type) | [part 2](https://8thlight.com/insights/using-the-option-type-effectively) - 8thlight
* :end: [Option Monads in Rust](http://hoverbear.org/2014/08/12/option-monads-in-rust/) - [Ana Hoverbear][]

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
* [Rust: A unique perspective](https://limpet.net/mbrubeck/2019/02/07/rust-a-unique-perspective.html) - Matt Brubeck
* [The Node Experiment - Exploring Async Basics with Rust](https://web.archive.org/web/20230125023131/https://cfsamson.github.io/book-exploring-async-basics/) - Carl Fredrik Samson
* [A closer look at Ownership in Rust](https://blog.thoughtram.io/ownership-in-rust/) - Pascal Precht
* [Understanding ownership in Rust](https://blog.logrocket.com/understanding-ownership-in-rust/) - Ukpai Ugochi

### Privacy

* :star: [Structure literals vs constructors in Rust](http://words.steveklabnik.com/structure-literals-vs-constructors-in-rust) - [Steve Klabnik][]

### Strings

* [String vs &str in Rust functions part 1](http://hermanradtke.com/2015/05/03/string-vs-str-in-rust-functions.html) | [part 2](http://hermanradtke.com/2015/05/06/creating-a-rust-function-that-accepts-string-or-str.html) | [part 3](http://hermanradtke.com/2015/05/29/creating-a-rust-function-that-returns-string-or-str.html) - [Herman J. Radtke III][]
* [From &str to Cow](https://jwilm.io/blog/from-str-to-cow/) - Joe Wilm
* [Rust: str vs String](http://www.ameyalokare.com/rust/2017/10/12/rust-str-vs-String.html) - Ameya Lokare
* [On dealing with owning and borrowing in public interfaces](https://phaazon.net/blog/on-owning-borrowing-pub-interface) - Dimitri Sabadie
* [Why Rust strings seem hard](https://www.brandons.me/blog/why-rust-strings-seem-hard) - Brandon Smith

### Syntax extensions

* :star: [Syntax extensions and regular expressions for Rust](http://blog.burntsushi.net/rust-regex-syntax-extensions/) - [Andrew Gallant][]

### Traits

* :star: [Abstraction without overhead: traits in Rust](http://blog.rust-lang.org/2015/05/11/traits.html) - [Aaron Turon][]
* [A series on trait objects part 1](https://huonw.github.io/blog/2015/01/peeking-inside-trait-objects) | [part 2](https://huonw.github.io/blog/2015/01/the-sized-trait) | [part 3](https://huonw.github.io/blog/2015/01/object-safety) | [part 4](https://huonw.github.io/blog/2015/05/where-self-meets-sized-revisiting-object-safety/) - [Huon Wilson][]
* [Rust traits for developer friendly libraries](https://benashford.github.io/blog/2015/05/24/rust-traits-for-developer-friendly-libraries/) - [Ben Ashford][]
* [Traits and trait objects](http://xania.org/201506/traits-and-trait-objects) - Matt Godbolt
* [Rust's Built-in Traits, the When, How & Why](https://llogiq.github.io/2015/07/30/traits.html) - [Llogiq][]
* [Where are you From::from](http://llogiq.github.io/2015/11/27/from-into.html) - [Llogiq][]
* [Gentle Intro to Type-level Recursion in Rust](https://beachape.com/blog/2017/03/12/gentle-intro-to-type-level-recursion-in-Rust-from-zero-to-frunk-hlist-sculpting/) - [Lloyd Chan][]
* [Traits and Trait Objects in Rust](https://joshleeb.com/posts/rust-traits-and-trait-objects/) - Josh Leeb-du Toit
* [A Quick Look at Trait Objects in Rust](https://tratt.net/laurie/blog/entries/a_quick_look_at_trait_objects_in_rust.html) - Laurence Tratt

### Unsafe

* [Unsafe Rust: An Intro and Open Questions](http://cglab.ca/~abeinges/blah/rust-unsafe-intro/) - [Alexis Beingessner][]
* [Memory Leaks are Memory Safe](https://huonw.github.io/blog/2016/04/memory-leaks-are-memory-safe/) - [Huon Wilson][]
* :star: [On Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/29/on-reference-counting-and-leaks/) - [Niko Matsakis][]
* :star: [A Few More Remarks on Reference Counting and Leaks](http://smallcultfollowing.com/babysteps/blog/2015/04/30/a-few-more-remarks-on-reference-counting-and-leaks/) - [Niko Matsakis][]
* [Pre-pooping Your Pants With Rust](http://cglab.ca/~abeinges/blah/everyone-poops/) - [Alexis Beingessner][]
* :star: [Unsafe Abstractions](http://smallcultfollowing.com/babysteps/blog/2016/05/23/unsafe-abstractions/) - [Niko Matsakis][]
* :star: [The "Tootsie Pop" Model for Unsafe Code](http://smallcultfollowing.com/babysteps/blog/2016/05/27/the-tootsie-pop-model-for-unsafe-code/) - [Niko Matsakis][]
* [Unsafe Rust is not C](https://www.youtube.com/watch?v=DG-VLezRkYQ) - Jack O'Connor

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

Are you searching for a rustacean? [http://www.rustaceans.org/](http://www.rustaceans.org/)

Do you want to ask a question? [Users Forum](https://users.rust-lang.org/), [Stack Overflow](https://stackoverflow.com/questions/tagged/rust)

Do you want to meet them IRL? [Meetup groups](http://www.meetup.com/topics/rust/), [Community calendar](https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com), [Community talks list](https://github.com/rust-community/talks), [RustBridge](https://rustbridge.github.io/)

Go to rusty events? [The 2018 Rust Event Lineup](https://blog.rust-lang.org/2018/01/31/The-2018-Rust-Event-Lineup.html), [The 2019 Rust Event Lineup](https://blog.rust-lang.org/2019/05/20/The-2019-Rust-Event-Lineup.html)

Are you looking for a job? [RustJobs.dev](https://rustjobs.dev/), [RustJobs.com](https://www.rustjobs.com/)

Are you fast, friendly, and fearless? [Find something Rusty to work on!](https://www.rustaceans.org/findwork/starters), [Awesome Rust Mentors](https://rustbeginners.github.io/awesome-rust-mentors/)

Do you want to stay up to date? [The official blog](https://blog.rust-lang.org/), [This Week in Rust](https://this-week-in-rust.org/), [This Week in Rust Docs](http://guillaumegomez.github.io/this-week-in-rust-docs/), [The official reddit](https://www.reddit.com/r/rust/)

Do you want to find out why some historical decisions took place? [Chronicle.rs](https://github.com/mgattozzi/chronicle.rs)

### Fearless Rust Bloggers

A complete list could be found [here](https://users.rust-lang.org/t/fearless-rust-bloggers/16770)

* [Aaron Turon][] - [blog](http://aturon.github.io/)
* [Andrew Gallant][] - [blog](http://blog.burntsushi.net/)
* [Ana Hoverbear][] - [blog](https://hoverbear.org/tags/#rust)
* [Brian Anderson][] - [blog](https://brson.github.io/blog/index.html)
* [Christoph Burgdorf][] - [blog](https://cburgdorf.wordpress.com/)
* [Chris Morgan][] - [blog](https://chrismorgan.info/blog/tags/rust/)
* [Felix S Klock II][] - [blog](http://blog.pnkfx.org/)
* [Huon Wilson][] - [blog](https://huonw.github.io/blog/)
* [Jonathan Turner][] - [blog](https://www.jntrnr.com/)
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
* Jonathan Pallant's [Rust on the Raspberry Pi tutorial (using a Sense HAT)](https://github.com/thejpster/pi-workshop-rs)

<!-- Rustaceans -->
[Aaron Turon]: https://github.com/aturon
[Alex Crichton]: https://github.com/alexcrichton
[Alexander Fadeev]: https://github.com/fadeevab
[Alexis Beingessner]: https://github.com/Gankro
[Andrew Gallant]: https://github.com/BurntSushi
[Ana Hoverbear]: https://github.com/Hoverbear
[Ben Ashford]: https://github.com/benashford
[Brian Anderson]: https://github.com/brson
[Carol Nichols]: https://github.com/carols10cents
[Chris Krycho]: https://github.com/chriskrycho
[Chris Morgan]: https://github.com/chris-morgan
[Christoph Burgdorf]: https://github.com/cburgdorf
[Daniel Keep]: https://github.com/DanielKeep
[Dan Callahan]: https://github.com/callahad
[David Tolnay]: https://github.com/dtolnay
[Felix S Klock II]: https://github.com/pnkfelix
[Herman J. Radtke III]: https://github.com/hjr3
[Jeena Lee]: https://github.com/jeenalee
[Jeremiah Peschka]: https://github.com/peschkaj
[Jim Blandy]: https://github.com/jimblandy
[Jorge Aparicio]: https://github.com/japaric
[Jonathan Turner]: https://github.com/jonathandturner
[Llogiq]: https://github.com/llogiq
[Luca Palmieri]: https://github.com/LukeMathWalker
[Lloyd Chan]: https://github.com/lloydmeta
[Huon Wilson]: https://github.com/huonw
[Manish Goregaokar]: https://github.com/Manishearth
[Michael Gattozzi]: https://github.com/mgattozzi
[Nick Cameron]: https://github.com/nrc
[Niko Matsakis]: https://github.com/nikomatsakis
[Pascal Hertleif]: https://github.com/killercup
[Patrick Walton]: https://github.com/pcwalton
[Steve Donovan]: https://github.com/stevedonovan
[Steve Klabnik]: https://github.com/steveklabnik
[Tim McNamara]: https://github.com/timClicks
[Yehuda Katz]: https://github.com/wycats
[Dumindu Madunuwan]: https://github.com/dumindu

## Similar projects

* [Curated Resources to Learn Rust](https://hackr.io/tutorials/learn-rust) - Hackr.io
* [Rust Anthology Master List](https://github.com/brson/rust-anthology/blob/master/master-list.md) - [Brian Anderson][]
* [Read Rust](https://readrust.net/)
