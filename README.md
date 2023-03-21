# Rust
Some Rust exercices

## Install Rust

Rust is required for this course!  The latest stable version is always recommended.

- Go to [rust-lang.org](https://rust-lang.org) and click on the `Get Started`
   button and follow the instructions to install Rust for your operating system.
   - Please DO NOT install rust via some other package manager.  It will probably be a version that is _really old_.

You should get somewhat similar output if you run commands like the ones below (newer versions are okay).  If you 
already have an old version of Rust installed, then run `rustup update` to install a newer version.

```shell
$ rustc --version
rustc 1.54.0 (a178d0322 2021-07-26)
$ cargo --version
cargo 1.54.0 (5ae8d74b3 2021-06-22)
```

# Exercises

Please clone this repository! These exercises are designed as Rust projects for you to edit on your
own computer, with the exception of Exercise A (which is just a `README.md` file).

The exercises are separate Rust projects inside the `exercises/` subdirectory.  For each exercise,
you should:
- Open the corresponding`exercise/EXERCISE_NAME` directory in your IDE/Editor
  - Seriously, just open the _individual exercise directory_ in your IDE. If you open the entire repository, your IDE will probably complain that it sees multiple Rust projects.
- Navigate to the same directory with your Terminal application (so you can run `cargo run`, etc.)
- Open up the `src/main.rs` file.
- Follow the numbered exercise instructions in the code comments.