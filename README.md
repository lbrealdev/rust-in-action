# rust-in-action

This repository is my guide to learning the [Rust](https://www.rust-lang.org/) language through the book [Rust in Action](https://www.rustinaction.com/).


# Install Rust

[Rustup](https://rustup.rs/): The Rust [installer](https://www.rust-lang.org/tools/install) and version management tool.
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

# About Rust

Rust is an expression-based language.

Note:

Converting source code into an executable file is called compiling. To compile Rust code, we need to install the Rust compiler and run it against the source code.


- Rust does not allow multiple places in an application to have write access to data.


Note:

- Data within Rust is immutable by default.
- Compile-time checks are strongly preferred. Safety should be a “zero-cost abstraction.”


# What is Rust ?

Rust is labelled as a systems programming language. Rust guarantees that your program is memory-safe without imposing any runtime costs.
The language’s first priority is safety.

A high-level syntax with low-level performance!


Strictness
It’s impossible—well, difficult—to be lazy when programming with Rust. Programs won’t compile until everything is just right. The compiler is strict, but helpful.


Rust is a general-purpose language



Rust code is stable, fast, and light on resources.
//  Under construction!!

### Goal of Rust: Safety

Rust programs are free from:

- Dangling pointers
- Data races
- Buffer overflow
- Iterator invalidation

### Goal of Rust: Productivity

Rust has many ergonomic features. It offers generics, sophisticated data types, pattern matching, and closures. Those who have worked with other ahead-of-time compilation languages are likely to appreciate Rust’s build system and its comprehensive package manager: cargo.

### Goal of Rust: Control

Rust offers programmers fine-grained control over how data structures are laid out in memory and their access patterns. While Rust uses sensible defaults that align with its “zero cost abstractions” philosophy, those defaults do not suit all situations.

===================

### Rust's big features

- Performance
- Concurrency
- Memory efficiency

#### Performance

Rust offers all of your computer’s available performance. Famously, Rust does not rely on a garbage collector to provide its memory safety.

#### Concurrency

Rust has spawned the expression fearless concurrency.

#### Memory efficiency

Rust enables you to create programs that require minimal memory.


### Compile times

Rust is slower at compiling code than its peer languages. It has a complex compiler toolchain that receives multiple intermediate representations and sends lots of code to the LLVM compiler. The unit of compilation for a Rust program is not an individual file but a whole package (known affectionately as a crate).

## TIP

Code with caution.

### With Rust, there are three main command_line tools to learn:
    - cargo, which manages a whole crate
    - rustup, which manages Rust installations
    - rustc, which manages compilation of Rust source code