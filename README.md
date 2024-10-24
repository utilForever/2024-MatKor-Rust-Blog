# 2024-MatKor-Rust-Blog

2024-MatKor-Rust-Blog is the material(lecture notes, examples and assignments) repository for learning Rust programming language and making a simple blog at Korea University Club 'MatKor' in 2024 Spring.

## Updates

- 2024-10-01: Added new contents for lecture "Closures" and renewed Assignment #6 and its solution.
- 2024-10-07: Added new contents for lecture "Macros" and renewed Assignment #7 and its solution.

## Contents

- Week 0 (3/18) [[Lecture]](./1%20-%20Lecture/240318%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%200.pdf)
  - Introduction
- Week 1 (3/18) [[Assignment]](./3%20-%20Assignment/240318%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%201/) [[Solution]](./4%20-%20Solution/240318%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%201/)
  - Hello, World
    - What is Rust?
    - Benefits of Rust
    - Playground
  - Types and Values
    - Hello, World
    - Variables
    - Values
    - Arithmetic
    - Type Inference
  - Control Flow Basics
    - `if` Expressions
    - Loops
    - `break` and `continue`
    - Blocks and Scopes
    - Functions
    - Macros
  - Tuples and Arrays
    - Arrays
    - Tuples
    - Array Iteration
    - Patterns and Destructuring
  - Assignment #1
- Week 2 (3/25) [[Assignment]](./3%20-%20Assignment/240325%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%202/) [[Solution]](./4%20-%20Solution/240325%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%202/)
  - References
    - Shared References
    - Exclusive References
    - Slices: `&[T]`
    - Strings
  - User-Defined Types
    - Named Structs
    - Tuple Structs
    - Enums
    - Static
    - Const
    - Type Aliases
  - Pattern Matching
    - Matching Values
    - Destructuring
    - Let Control Flow
  - Methods and Traits
    - Methods
    - Traits
    - Deriving
  - Assignment #2
- Week 3 (4/1) [[Assignment]](./3%20-%20Assignment/240401%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%203/) [[Solution]](./4%20-%20Solution/240401%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%203/)
  - Generics
    - Generic Functions
    - Generic Data Types
    - Generic Traits
    - `impl` Trait
  - Standard Library Types
    - Standard Library
    - Documentation
    - `Option`
    - `Result`
    - `String`
    - `Vec`
    - `HashMap`
  - Standard Library Traits
    - Comparisons
    - Operators
    - `From` and `Into`
    - Casting
    - `Read` and `Write`
    - `Default`, struct update syntax
    - Closures
  - Assignment #3
- Week 4 (4/8) [[Assignment]](./3%20-%20Assignment/240408%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%204/) [[Solution]](./4%20-%20Solution/240408%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%204/)
  - Memory Management
    - Review of Program Memory
    - Approaches to Memory Management
    - Onwership
    - Move Semantics
    - `Clone`
    - `Copy` Types
    - `Drop`
  - Smart Pointers
    - `Box`
    - `Rc`
    - Trait Objects
  - Borrowing
    - Borrowing a Value
    - Borrow Checking
    - Interior Mutability
  - Lifetimes
    - Lifetime Annotations
    - Lifetime Elision
    - Struct Lifetimes
  - Assignment #4
- Week 5 (4/29) [[Assignment]](./3%20-%20Assignment/240429%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%205/) [[Solution]](./4%20-%20Solution/240429%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%205/)
  - Iterators
    - `Iterator`
    - `IntoIterator`
    - `FromIterator`
  - Modules
    - Modules
    - Filesystem Hierarchy
    - Visibility
    - `use`, `super`, `self`
  - Testing
    - Test Modules
    - Other Types of Tests
    - Compiler Lints and Clippy
  - Error Handling
    - Panics
    - Try Operator
    - Try Conversions
    - `Error` Trait
    - `thiserror` and `anyhow`
  - Unsafe Rust
    - Unsafe
    - Dereferencing Raw Pointers
    - Mutable Static Variables
    - Unions
    - Unsafe Functions
    - Unsafe Traits
  - Assignment #5
- Week 6 (5/13) [[Lecture]](./1%20-%20Lecture/240513%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%206.pdf) [[Example]](./2%20-%20Example/240513%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%206/) [[Assignment]](./3%20-%20Assignment/240513%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%206/) [[Solution]](./4%20-%20Solution/240513%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%206/)
  - Closures
    - Capturing Variables
      - Closures that Borrow
      - Closures that Steal
    - Function and Closure Types
    - Closure Performance
    - Closures and Safety
      - Closures that Kill
      - `FnOnce`
      - `FnMut`
      - `Copy` and `Clone` for Closures
    - Callbacks
    - Using Closures Effectively
  - Assignment #6
- Week 7 (5/20) [[Lecture]](./1%20-%20Lecture/240520%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%207.pdf) [[Example]](./2%20-%20Example/240520%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%207/) [[Assignment]](./3%20-%20Assignment/240520%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%207/) [[Solution]](./4%20-%20Solution/240520%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%207/)
  - Macros
    - Macro Basics
      - Basics of Macro Expansion
      - Unintended Consequences
      - Repetition
    - Built-in Macros
    - Debugging Macros
    - Building the `json!` Macro
      - Fragment Types
      - Recursion in Macros
      - Using Traits with Macros
      - Scoping and Hygiene
      - Importing and Exporting Macros
    - Avoiding Syntax Errors During Matching
    - Beyond macro_rules!
  - Assignment #7
- Week 8 (5/27) [[Lecture]](./1%20-%20Lecture/240527%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%208.pdf) [[Example]](./2%20-%20Example/240527%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%208/) [[Assignment]](./3%20-%20Assignment/240527%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%208/) [[Solution]](./4%20-%20Solution/240527%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%208/)
  - Concurrency, Part 1
    - Fork-Join Parallelism
      - `spawn` and `join`
      - Error Handling Across Threads
      - Sharing Immutable Data Across Threads
      - `Rayon`
    - Channels
      - Sending Values
      - Receiving Values
      - Running the Pipeline
      - Channel Features and Performance
      - Thread Safety: `Send` and `Sync`
      - Piping Almost Any Iterator to a Channel
      - Beyond Pipelines
  - Assignment #8
- Week 9 (6/3) [[Lecture]](./1%20-%20Lecture/240603%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%209.pdf) [[Assignment]](./3%20-%20Assignment/240603%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%209/) [[Solution]](./4%20-%20Solution/240603%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%209/)
  - Concurrency, Part 2
    - Shared Mutable State
      - What Is a Mutex?
      - `Mutex<T>`
      - `mut` and `Mutex`
      - Why Mutexes Are Not Always a Good Idea
      - Deadlock
      - Poisoned Mutexes
      - Multiconsumer Channels Using Mutexes
      - Read/Write Locks (`RwLock<T>`)
      - Condition Variables (`Condvar`)
      - Atomics
      - Global Variables
  - Assignment #9
- Week 10 (7/1) [[Lecture]](./1%20-%20Lecture/240701%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%2010.pdf)
  - Asynchronous Programming, Part 1
    - From Synchronous to Asynchronous
      - Futures
      - Async Functions and Await Expressions
      - Calling Async Functions from Synchronous Code: `block_on`
      - Spawning Async Tasks
      - Async Blocks
      - Building Async Functions from Async Blocks
      - Spawning Async Tasks on a Thread Pool
      - But Does Your Future Implement `Send`?
      - Long Running Computations: `yield_now` and `spawn_blocking`
      - Comparing Asynchronous Designs
      - A Real Asynchronous HTTP Client
- Week 11 (7/10) [[Lecture]](./1%20-%20Lecture/240710%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%2011.pdf) [[Example]](./2%20-%20Example/240710%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%2011/)
  - Asynchronous Programming, Part 2
    - From Synchronous to Asynchronous
      - But Does Your Future Implement `Send`?
      - Long Running Computations: `yield_now` and `spawn_blocking`
      - Comparing Asynchronous Designs
      - A Real Asynchronous HTTP Client
    - An Asynchronous Client and Server
      - Error and Result Types
      - The Protocol
      - Talking User Input: Asynchronous Streams
      - Sending Packets
      - Receving Packets: More Asynchronous Streams
      - The Client's Main Function
- Week 12 (8/1) [[Lecture]](./1%20-%20Lecture/240801%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%2012.pdf) [[Example]](./2%20-%20Example/240801%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%2012/)
  - Asynchronous Programming, Part 3
    - An Asynchronous Client and Server
      - The Server's Main Function
      - Handling Chat Connections: Async Mutexes
      - The Group Table: Synchronous Mutexes
      - Chat Groups: `tokio`'s Broadcast Channels
    - Primitive Futures and Executors: When Is a Future Worth Polling Again?
- Week 13 (8/6) [[Lecture]](./1%20-%20Lecture/240806%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%2013.pdf) [[Example]](./2%20-%20Example/240806%20-%20Rust%20Basic%20+%20Make%20a%20Blog,%20Week%2013/)
  - Asynchronous Programming, Part 4
    - Primitive Futures and Executors: When Is a Future Worth Polling Again?
      - Invoking Wakers: `spawn_blocking`
      - Implementing `block_on`
    - Pinning
      - The Two Life Stages of a Future
      - Pinned Pointers
      - The `Unpin` 
    - When Is Asynchronous Code Helpful?
  - Assignment #10
- Week 14 (TBA)
  - Foreign Function Interface (FFI)
  - Rust and WebAssembly
  - Assignment #11

## References

- Beginner
  * [The Rust Programming Language](https://doc.rust-lang.org/book/)
  * [Rust-101 by Ralf Jung](https://www.ralfj.de/projects/rust-101/main.html)
  * [Comprehensive Rust](https://google.github.io/comprehensive-rust/)
  * [Rustlings](https://github.com/rust-lang/rustlings/)
  * [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/)
  * [Exercism - Rust](https://exercism.org/tracks/rust)
  * [Book: The Rust Programming Language](http://www.yes24.com/Product/Goods/83075894)
  * [Book: Rust in Action](https://www.manning.com/books/rust-in-action)
  * [Book: Programming Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)
- Intermediate
  * [The Standard Library](https://doc.rust-lang.org/std/index.html)
  * [The Edition Guide](https://doc.rust-lang.org/edition-guide/index.html)
  * [The Cargo Book](https://doc.rust-lang.org/cargo/index.html)
  * [The rustdoc Book](https://doc.rust-lang.org/rustdoc/index.html)
  * [The rustc Book](https://doc.rust-lang.org/rustc/index.html)
  * [Book: Concurrent Programming](http://www.yes24.com/Product/Goods/108570426)
  * [Book: Rust for Rustaceans](https://rust-for-rustaceans.com/)
- Advanced
  * [The Rust Reference](https://doc.rust-lang.org/reference/index.html)
  * [The Rustonomicon](https://doc.rust-lang.org/nomicon/index.html)
  * [The Rust Unstable Book](https://doc.rust-lang.org/nightly/unstable-book/index.html)

## How To Contribute

Contributions are always welcome, either reporting issues/bugs or forking the repository and then issuing pull requests when you have completed some additional coding that you feel will be beneficial to the main project. If you are interested in contributing in a more dedicated capacity, then please contact me.

## Contact

You can contact me via e-mail (utilForever at gmail.com). I am always happy to answer questions or help with any issues you might have, and please be sure to share any additional work or your creations with me, I love seeing what other people are making.

## License

<img align="right" src="https://149753425.v2.pressablecdn.com/wp-content/uploads/2009/06/OSIApproved_100X125.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2024 [Chris Ohk](http://www.github.com/utilForever).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
