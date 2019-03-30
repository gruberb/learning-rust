# Learning Rust
Material I come across which is benefitial to read through to learn the language ([next to my own series, of course](https://github.com/gruberb/web-programming-in-rust))

---
# Content 

## Rust Overview
1. [General Overview](#general-overview)
2. [Rust Features](#rust-features)  
    2.1 [Traits](#traits)  
    2.2 [Types](#types)  
    2.3 [Associated Types](#associated-types)  
    2.4 [Closures](#closures)  
    2.5 [Ownership](#ownership)  
    2.6 [Allocation and Memory](#allocation-and-lifetimes)  
    2.7 [Lifetimes](#lifetimes)  
    2.8 [Macros](#maros)  
    2.9 [Cargo](#cargo)  
3. [Specific Knowledge](#specific-knowledge)  
    3.1 [Iterator](#iterator)  
    3.2 [Options](#options)  
    3.3 [Documentation Testing](#documentation-testing)  
4. [Complete Learning Websites](#complete-learning-websites)  
5. [Tutorials](#tutorials)  
6. [Talks](#talks)
7. [Project Ideas](#project-ideas)
8. [General Tinker](#general-tinker)
9. [Long form and General Knowledge](#long-form-and-general-knowledge)

## Rust Asnyc/Web
1. [Async](#async)
2. [Concurrency](#concurrency)
3. [Futures](#futures)
4. [Libraries](#libraries)
5. [Tide](#tide)
6. [Interesting Projects](#interesting-projects)
7. [Specific Knowledge](#specific-knowledge)
8. [General Web and Async KnowHow](#general-web-and-async-knowhow)
9. [Async Tinker](#async-tinker)
10. [Insight in other languages](#insight-in-other-languages)

---
## General Overview
* [Rust for High-Level Programming Language Developers – IQDevs – Technology Excellence Redefined](https://iqdevs.github.io/Rust-for-High-Level-Programming-Language-Developers/)
* [Learning-Rust/main.rs at master · Mathieu-Desrochers/Learning-Rust · GitHub](https://github.com/Mathieu-Desrochers/Learning-Rust/blob/master/src/main.rs)
* [Oxide : The Essence of Rust](https://arxiv.org/pdf/1903.00982.pdf)
* [Structure literals vs constructors in Rust](https://words.steveklabnik.com/structure-literals-vs-constructors-in-rust)

## Rust Features
### Traits
* [Rust: Traits – | ?- BlogName = _.](https://gillesleblanc.wordpress.com/2014/11/21/rust-traits/)
* [Abstraction without overhead: traits in Rust - The Rust Programming Language Blog](https://blog.rust-lang.org/2015/05/11/traits.html)
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

## Talks
* [Rust - YouTube](https://www.youtube.com/channel/UCaYhcUwRBNscFNUKTjgPFiA/videos)
* [GOTO 2018 • Zen and the Art of Convincing Your Company to Use Rust • Ashley Williams - YouTube](https://www.youtube.com/watch?feature=youtu.be&v=Pn-1so-Ibsg&app=desktop)
* [RustConf 2017 - Building Rocket by Sergio Benitez - YouTube](https://www.youtube.com/watch?v=t_FUZ34ahBE&feature=youtu.be)
* [RustConf 2018 - No Spaghetti: Designing for Understanding by  Brandon W. Maister - YouTube](https://youtu.be/2uBbjq-Trnk)
* [TechCast #108 – Carol Nichols on Rust – Chariot Solutions](https://chariotsolutions.com/podcast/carol-nichols-rust/)
* [A Case for Oxidation: The Rust Programming Language - YouTube](https://youtu.be/cDFSrVhnZKo)

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
* [Green Threads are like Garbage Collection](https://www.fpcomplete.com/blog/2017/01/green-threads-are-like-garbage-collection)
* [Test harness - Wikipedia](https://en.wikipedia.org/wiki/Test_harness)

---

## Async
* [Async, futures, and tokio - Rust Crash Course lesson 7](https://www.snoyman.com/blog/2018/12/rust-crash-course-07-async-futures-tokio)
* [async/await notation for ergonomic asynchronous IO Pull Request](https://github.com/rust-lang/rfcs/pull/2394/files)
* [asynchronous - What is the purpose of async/await in Rust?](https://stackoverflow.com/questions/52835725/what-is-the-purpose-of-async-await-in-rust)
* [The relationship between async libraries in Rust](https://www.jimmycuadra.com/posts/the-relationship-between-async-libraries-in-rust/)
* [RFC: stabilize `std::task` and `std::future::Future`](https://github.com/aturon/rfcs/blob/e7eaea194994da28bde2c36d78fedf50e79b4bcf/text/2592-futures.md)

## Concurrency
* [Fearless Concurrency - The Rust Programming Language](https://doc.rust-lang.org/1.30.0/book/second-edition/ch16-00-concurrency.html)
* [Green Threads are like Garbage Collection](https://www.fpcomplete.com/blog/2017/01/green-threads-are-like-garbage-collection)
* [Sending trait objects between threads - help - The Rust Programming Language Forum](https://users.rust-lang.org/t/sending-trait-objects-between-threads/2374)
* [std::sync::Arc - Rust](https://doc.rust-lang.org/std/sync/struct.Arc.html)
* [Is Send/Sync special cased? - The Rust Programming Language Forum](https://users.rust-lang.org/t/is-send-sync-special-cased/2355/2)
* [What is a Thread?](https://www.geeksforgeeks.org/operarting-system-thread/)

## Futures
* [Understanding Futures In Rust — Part 1 | Viget](https://www.viget.com/articles/understanding-futures-in-rust-part-1/)
* [Futures in Rust (and Haskell)](https://slides.com/wraithm/async-io-in-rust-and-haskell/#/)
* [Converting AsyncRead and AsyncWrite to Futures, Sinks and Streams](https://jsdw.me/posts/rust-futures-tokio/)
* [Zero-cost futures in Rust · Aaron Turon](https://aturon.github.io/blog/2016/08/11/futures/)


## Libraries
* Futures: [Zero-cost asynchronous programming in Rust](https://github.com/rust-lang-nursery/futures-rs)
* Romio: [Wherefore art thou Romio?](https://boats.gitlab.io/blog/post/romio/) , [GitHub - withoutboats/romio: asynchronous networking primitives](https://github.com/withoutboats/romio)
* Juliex: [GitHub - withoutboats/juliex](https://github.com/withoutboats/juliex)
* Tower:  [GitHub - tower-rs/tower: fn(Request) -> Future<Response>](https://github.com/tower-rs/tower)
* Serde: [GitHub - serde-rs/serde: Serialization framework for Rust](https://github.com/serde-rs/serde)
* HTTP-Service: [GitHub - rustasync/http-service: Types and traits for http-based services using the latest futures API](https://github.com/rustasync/http-service)
* Tokio: [Tokio - The asynchronous run-time for the Rust programming language.](https://tokio.rs/)

## Tide
* [WIP New Tide middleware: Automatic compression handling by kimsnj · Pull Request #117 · rustasync/tide · GitHub](https://github.com/rustasync/tide/pull/117/files)
* [URL generation · Issue #24 · rustasync/tide · GitHub](https://github.com/rustasync/tide/issues/24)
* [Logging middleware · Issue #8 · rustasync/tide · GitHub](https://github.com/rustasync/tide/issues/8)
* [An RFC for structured logging by KodrAus · Pull Request #296 · rust-lang-nursery/log · GitHub](https://github.com/rust-lang-nursery/log/pull/296)
* [Nail down wildcard/fallback rules · Issue #12 · rustasync/tide · GitHub](https://github.com/rustasync/tide/issues/12)
* [Extend extractors with an optional seed per endpoint. by HeroicKatora · Pull Request #126 · rustasync/tide · GitHub](https://github.com/rustasync/tide/pull/126)
* [WIP Revamp Tide, dropping Extractors and simplifying the framework by aturon · Pull Request #156 · rustasync/tide · GitHub](https://github.com/rustasync/tide/pull/156/files)
* [Nail down wildcard/fallback rules · Issue #12 · rustasync/tide · GitHub](https://github.com/rustasync/tide/issues/12)
* [Consider using route_recognizer instead of path-table · Issue #141 · rustasync/tide · GitHub](https://github.com/rustasync/tide/issues/141)
* [Gotham Example](https://github.com/gotham-rs/gotham/edit/master/examples/cookies/introduction/src/main.rs)

## Interesting projects
* [rust-ipfs-api: Rust crate for interfacing with the IPFS API](https://github.com/gkbrk/rust-ipfs-api)
* [Radicle 🌱](http://www.radicle.xyz/)
* [ffsend: Easily and securely share files from the command line](https://github.com/timvisee/ffsend)
* [rust-imap: IMAP client library](https://github.com/jonhoo/rust-imap)
* [Ramhorns: Dynamic templates](https://maciej.codes/2019-03-03-ramhorns.html)
* [May - coroutines in Rust](https://github.com/Xudong-Huang/may)

## Specific Knowledge
* [Tokio Reactor](https://docs.rs/tokio/0.1.18/tokio/reactor/index.html)

## General Web and Async KnowHow
* [The Illustrated TLS 1.3 Connection: Every Byte Explained](https://tls13.ulfheim.net/)
* [corefx/HttpCorrelationProtocol.md at master · dotnet/corefx · GitHub](https://github.com/dotnet/corefx/blob/master/src/System.Diagnostics.DiagnosticSource/src/HttpCorrelationProtocol.md)
* [Transport Layer Security - Wikipedia](https://en.wikipedia.org/wiki/Transport_Layer_Security)
* [Finite-state machine - Wikipedia](https://en.wikipedia.org/wiki/Finite-state_machine)
* [There is no free lunch](http://www.gotw.ca/publications/concurrency-ddj.htm)

## Async Tinker
* [Sending trait objects between threads](https://users.rust-lang.org/t/sending-trait-objects-between-threads/2374)
* [Event Stream in AWS Lambda](https://github.com/awslabs/aws-lambda-rust-runtime/blob/7aad06ad0a9c814a697202dff77ba293aa32dc62/lambda-runtime-client-simple/src/lib.rs#L155)
* [How do I use asnyc/await syntax in Tokio?](https://stackoverflow.com/questions/54853917/how-do-i-use-async-await-syntax-with-tokio)

## Insight in other languages
* [Go concurrency](https://tour.golang.org/concurrency/2)
* [Object Streams in NodeJS](https://community.risingstack.com/the-definitive-guide-to-object-streams-in-node-js/)
