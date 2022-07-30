# Cargo

Commands and functions of the [Cargo](https://doc.rust-lang.org/cargo/index.html) Rust package manager.

-----------------------------

What is Cargo ?
* Cargo is the Rust package manager. 
-----------------------------

# Use

We can see that cargo is a front-end to rustc, the Rust compiler, but cargo provides several additional utilities, including the following:

Creates a skeleton Rust project in a new directory:
```
cargo new <project-name>
```

Creates a Rust project using the current directory:
```
cargo init
```

Run the current package, executes `cargo build` and then also runs the resulting executable file.:
```
cargo run


# Run optimized artifacts with the `release` profile.
cargo run -q --release or cargo -q -r
```

Downloads dependencies and compiles the code:
```
cargo build
```

Builds HTML documentation for every dependency in the current project:
```
cargo doc
```