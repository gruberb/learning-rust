# Learning Rust
Material I come across which is beneficial to read through to learn the language.

---
# Content

## Rust Overview
0. [Shamelss Plugs](#shameless-plugs)
1. [General Overview](#general-overview)
2. [Idiomatic Rust](#idiomatic-rust)
3. [Rust Features](#rust-features)
    3.1 [Traits](#traits)
    3.2 [Types](#types)
    3.3 [Associated Types](#associated-types)
    3.4 [Closures](#closures)
    3.5 [Ownership](#ownership)
    3.6 [Allocation and Memory](#allocation-and-lifetimes)
    3.7 [Lifetimes](#lifetimes)
    3.8 [Macros](#maros)
    3.9 [Cargo](#cargo)
4. [specific Knowledge](#specific-knowledge)
    4.1 [Iterator](#iterator)
    4.2 [Options](#options)
    4.3 [Documentation Testing](#documentation-testing)
5. [Complete Learning Websites](#complete-learning-websites)
6. [Tutorials](#tutorials)
7. [Project Ideas](#project-ideas)
8. [General Tinker](#general-tinker)
9. [Long form and General Knowledge](#long-form-and-general-knowledge)

## Rust Async/Web
1. [Async](#async)
2. [Concurrency](#concurrency)
3. [Futures](#futures)
4. [TCP, epoll, channels](#TCP,-epoll,-channels)
5. [gRPC](#grpc)
6. [Libraries](#libraries)
7. [Interesting Projects](#interesting-projects)
8. [General Web and Async KnowHow](#general-web-and-async-knowhow)

## Peer-to-Peer
1. [libp2p](#libp2p)

---

## Shameless plugs
* [Rust Web Development book (Manning)](https://www.manning.com/books/rust-web-development)
* [rustwebdevelopment.com](https://rustwebdevelopment.com)

## General Overview
* [Rust for High-Level Programming Language Developers – IQDevs – Technology Excellence Redefined](https://iqdevs.github.io/Rust-for-High-Level-Programming-Language-Developers/)
* [Learning-Rust/main.rs at master · Mathieu-Desrochers/Learning-Rust · GitHub](https://github.com/Mathieu-Desrochers/Learning-Rust/blob/master/src/main.rs)
* [Oxide : The Essence of Rust](https://arxiv.org/pdf/1903.00982.pdf)
* [Structure literals vs constructors in Rust](https://words.steveklabnik.com/structure-literals-vs-constructors-in-rust)

## Idiomatic Rust
* [Binary Search in Rust](https://shane-o.dev/blog/binary-search-rust)
* [Building a middleware from Scratch](https://github.com/tower-rs/tower/blob/master/guides/building-a-middleware-from-scratch.md)
* [Iterators in Rust](https://www.newline.co/@uint/rust-iterators-a-guide--80e35528)
* [Elegant APIs in Rust](https://deterministic.space/elegant-apis-in-rust.html)

## Rust Features
### Traits
* [Abstraction without overhead: traits in Rust - The Rust Programming Language Blog](https://blog.rust-lang.org/2015/05/11/traits.html)
* [Refactoring in Rust - Using Traits](https://fettblog.eu/refactoring-rust-introducing-traits/)
* [Using traits for better testing](https://stackoverflow.com/questions/72817819/how-do-i-use-rust-traits-to-abstract-http-call-for-tests)
* [Rust traits and dependecny injection](https://jmmv.dev/2022/04/rust-traits-and-dependency-injection.html)
* [Advanced traits](https://doc.rust-lang.org/book/ch19-03-advanced-traits.html#specifying-placeholder-types-in-trait-definitions-with-associated-types)
* [Rust Basics: the add Trait - Hashnode](https://chilimatic.hashnode.dev/rust-basics-the-add-trait-cjtoke4yh002t8hs1c61p82mz)

### Types
* [A Gentle Introduction to Practical Types | Patterns in Cyberspace](https://leotindall.com/tutorial/a-gentle-introduction-to-practical-types/)

### Associated Types
* [Advanced Traits - The Rust Programming Language](https://doc.rust-lang.org/book/ch19-03-advanced-traits.html#specifying-placeholder-types-in-trait-definitions-with-associated-types)

### Closures
* [Closures: Anonymous Functions that Can Capture Their Environment - The Rust Programming Language](https://doc.rust-lang.org/book/ch13-01-closures.html)
* [Finding Closure in Rust |  Huon on the internet](http://huonw.github.io/blog/2015/05/finding-closure-in-rust/)

### Ownership
* [Ownership in Rust, Part 1 – Thomas Countz – Medium](https://medium.com/@thomascountz/ownership-in-rust-part-1-112036b1126b)
* [Ownership in Rust, Part 2 – Thomas Countz – Medium](https://medium.com/@thomascountz/ownership-in-rust-part-2-c3e1da89956e)
* [Rust: Unlocking Systems Programming](https://www.infoq.com/presentations/rust-thread-safety)
* [Stacked Borrows Implemented](https://www.ralfj.de/blog/2018/11/16/stacked-borrows-implementation.html)

### Allocation and Memory
* [Allocations in Rust - speice.io](https://speice.io/2019/02/understanding-allocations-in-rust.html)

### Lifetimes
* [Rust Lifetimes for the Uninitialised](https://asquera.de/blog/2018-01-29/rust-lifetimes-for-the-uninitialised/)
* [Why can lifetimes not be inferred? - help - The Rust Programming Language Forum](https://users.rust-lang.org/t/why-can-lifetimes-not-be-inferred/25645)
* [Lifetimes in Rust - Stack Overflow](https://stackoverflow.com/questions/17490716/lifetimes-in-rust?rq=1)
* [Generic Types, Traits, and Lifetimes - The Rust Programming Language](https://doc.rust-lang.org/book/ch10-00-generics.html)

### Macros
* [A Practical Intro to Macros in Rust 1.0](https://danielkeep.github.io/practical-intro-to-macros.html)
* [The Little Book of Rust Macros](https://danielkeep.github.io/tlborm/book/README.html)
* [Deriving Traits in Rust with Procedural Macros · naftuli.wtf](https://naftuli.wtf/2019/01/02/rust-derive-macros/)
* [A Love Letter To RusT Macros](https://happens.lol/posts/a-love-letter-to-rust-macros/)

### Cargo
* [Matthias Endler](https://matthias-endler.de/2018/cargo-inspect/)

## Specific Knowledge
### Iterator
* [std::iter::Iterator - Rust](https://doc.rust-lang.org/std/iter/trait.Iterator.html)

### Options
* [Rust: Using Options by example](http://www.ameyalokare.com/rust/2017/10/23/rust-options.html)

### Documentation Testing
* [rust-by-example](https://doc.rust-lang.org/rust-by-example/testing/doc_testing.html)

---

## Complete Learning Websites
* [Learning Rust](https://learning-rust.github.io/)
* [Exercism.io - Rust track](https://exercism.io/tracks/rust)
* [Rust Cookbook]( https://rust-lang-nursery.github.io/rust-cookbook/intro.html)
* [Rustlings](https://github.com/rust-lang/rustlings)

## Tutorials
* [Writing an OS in Rust](https://os.phil-opp.com/)
* [Streaming gRPC with Rust – Kevin Hoffman – Medium](https://medium.com/@KevinHoffman/streaming-grpc-with-rust-d978fece5ef6)
* [Introduction - Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)
* [Stanford CS140e - Operating Systems](https://github.com/dddrrreee/cs140e-win19)
* [Implementing TCP in Rust (part 1) - YouTube](https://www.youtube.com/watch?v=bzja9fQWzdA)
* [Build a cryptocurrency! - Blockchain in Rust #01: Blocks & Hashing - YouTube](https://www.youtube.com/watch?v=vJdT05zl6jk&list=PLwnSaD6BDfXL0RiKT_5nOIdxTxZWpPtAv&index=2&t=0s)
* [Learn Parser Combinators](https://bodil.lol/parser-combinators/)

## Project Ideas
* [Classic unix utilities make great beginner projects! : rust](https://www.reddit.com/r/rust/comments/b0i625/classic_unix_utilities_make_great_beginner/)

## General Tinker
* [Understand this assembly output](https://godbolt.org/z/SYMUem)
* [Understand this example code](https://play.rust-lang.org/?version=stable&mode=debug&edition=2018&gist=1ca846311b58545aa1a0c7475360f916)
* [Rust pattern: Iterating an over a Rc<Vec<T>>](http://smallcultfollowing.com/babysteps/blog/2018/09/02/rust-pattern-iterating-an-over-a-rc-vec-t/)
* [State Machine Patterns in Rust](https://hoverbear.org/2016/10/12/rust-state-machine-pattern/)

## Long form and General Knowledge
* [Scientific computing: a Rust adventure Part 0 - Vectors](https://www.lpalmieri.com/posts/2019-02-23-scientific-computing-a-rust-adventure-part-0-vectors/)
* [Scientific computing: a Rust adventure Part 1 - Zero-cost abstractions](https://www.lpalmieri.com/posts/2019-03-12-scientific-computing-a-rust-adventure-part-1-zero-cost-abstractions/)
* [Test harness - Wikipedia](https://en.wikipedia.org/wiki/Test_harness)

---

## Async
* [What Are Tokio and Async IO All About?](https://manishearth.github.io/blog/2018/01/10/whats-tokio-and-async-io-all-about/)
* [Async, futures, and tokio - Rust Crash Course lesson 7](https://www.snoyman.com/blog/2018/12/rust-crash-course-07-async-futures-tokio)
* [async/await notation for ergonomic asynchronous IO Pull Request](https://github.com/rust-lang/rfcs/pull/2394/files)
* [asynchronous - What is the purpose of async/await in Rust?](https://stackoverflow.com/questions/52835725/what-is-the-purpose-of-async-await-in-rust)
* [The relationship between async libraries in Rust](https://www.jimmycuadra.com/posts/the-relationship-between-async-libraries-in-rust/)
* [RFC: stabilize `std::task` and `std::future::Future`](https://github.com/aturon/rfcs/blob/e7eaea194994da28bde2c36d78fedf50e79b4bcf/text/2592-futures.md)

## Concurrency
* [Green Threads are like Garbage Collection](https://www.fpcomplete.com/blog/2017/01/green-threads-are-like-garbage-collection)
* [Fearless Concurrency - The Rust Programming Language](https://doc.rust-lang.org/1.30.0/book/second-edition/ch16-00-concurrency.html)
* [Sending trait objects between threads - help - The Rust Programming Language Forum](https://users.rust-lang.org/t/sending-trait-objects-between-threads/2374)
* [std::sync::Arc - Rust](https://doc.rust-lang.org/std/sync/struct.Arc.html)
* [Is Send/Sync special cased? - The Rust Programming Language Forum](https://users.rust-lang.org/t/is-send-sync-special-cased/2355/2)
* [What is a Thread?](https://www.geeksforgeeks.org/operarting-system-thread/)
* [Tokio: Tutorial](https://tokio.rs/tokio/tutorial)

## Futures
* [Futures in Rust](https://www.youtube.com/watch?v=9_3krAQtD2k)
* [Understanding Futures In Rust — Part 1 | Viget](https://www.viget.com/articles/understanding-futures-in-rust-part-1/)
* [Futures in Rust (and Haskell)](https://slides.com/wraithm/async-io-in-rust-and-haskell/#/)
* [Converting AsyncRead and AsyncWrite to Futures, Sinks and Streams](https://jsdw.me/posts/rust-futures-tokio/)
* [Zero-cost futures in Rust · Aaron Turon](https://aturon.github.io/blog/2016/08/11/futures/)

## TCP, epoll, channels
* [TCP in Rust - #1](https://www.youtube.com/watch?v=bzja9fQWzdA&)
* [TCP in Rust - #2](https://www.youtube.com/watch?v=OCpt1I0MWXE)
* [TCP in Rust - #3](https://www.youtube.com/watch?v=8GE6ltLRJA4)
* [Channels in Rust](https://www.youtube.com/watch?v=b4mS5UPHh20)
* [epoll with Rust](https://zupzup.org/epoll-with-rust/)

## gRPC
* [Building gRPC APIs with Rust](https://konghq.com/blog/building-grpc-apis-with-rust)
* [gRPC load balancing with Rust](https://truelayer.com/blog/grpc-load-balancing-in-rust/)

## Libraries
* Futures: [Zero-cost asynchronous programming in Rust](https://github.com/rust-lang-nursery/futures-rs)
* Tower:  [GitHub - tower-rs/tower: fn(Request) -> Future<Response>](https://github.com/tower-rs/tower)
* Serde: [GitHub - serde-rs/serde: Serialization framework for Rust](https://github.com/serde-rs/serde)
* Tokio: [Tokio - The asynchronous run-time for the Rust programming language.](https://tokio.rs/)
* Axum: [Axum - Web framework](https://github.com/tokio-rs/axum)

## Interesting projects
* [rust-ipfs-api](https://github.com/gkbrk/rust-ipfs-api)
* [Radicle](http://www.radicle.xyz/)
* [ffsend:Share files from the command line](https://github.com/timvisee/ffsend)
* [rust-imap: IMAP client library](https://github.com/jonhoo/rust-imap)

## General Web and Async KnowHow
* [Concurrency, Parallelism, Threads, Processes, Async and Sync](https://medium.com/swift-india/concurrency-parallelism-threads-processes-async-and-sync-related-39fd951bc61d)
* [The Illustrated TLS 1.3 Connection: Every Byte Explained](https://tls13.ulfheim.net/)
* [corefx/HttpCorrelationProtocol.md ](https://github.com/dotnet/corefx/blob/master/src/System.Diagnostics.DiagnosticSource/src/HttpCorrelationProtocol.md)
* [Transport Layer Security - Wikipedia](https://en.wikipedia.org/wiki/Transport_Layer_Security)
* [Finite-state machine - Wikipedia](https://en.wikipedia.org/wiki/Finite-state_machine)
* [There is no free lunch](http://www.gotw.ca/publications/concurrency-ddj.htm)
* [Reactor Pattern](https://www.puncsky.com/blog/2015/01/13/understanding-reactor-pattern-for-highly-scalable-i-o-bound-web-server/)

## Peer-to-Peer
### libp2p
* [What is libp2p](https://docs.libp2p.io/concepts/introduction/overview/)
* [Adressing in libp2p](https://github.com/libp2p/specs/blob/master/addressing/README.md)
* [PeerIds and keys](https://github.com/libp2p/specs/blob/master/peer-ids/peer-ids.md)
* [Create a libp2p node](https://curriculum.pl-launchpad.io/curriculum/libp2p/core-concepts/)
* [Distributed hash table](https://docs.libp2p.io/concepts/appendix/glossary/#dht)
* [libp2p swarm](https://docs.rs/libp2p/latest/libp2p/swarm/index.html)
* [Chat example](https://github.com/libp2p/rust-libp2p/blob/master/examples/chat-example/src/main.rs)
* [Ping example](https://github.com/gruberb/libp2p-rs-ping/blob/main/src/main.rs)
* [Tutorial: Build a simple p2p app using Rust](https://morioh.com/p/f1b14f97b537)
