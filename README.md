# rust

⚙️ Rust lang Study Repository.

## [00 - Basic](https://doc.rust-lang.org/book/ch01-02-hello-world.html)

A little bit of the basics.!

### What have learned?

- Use underscore `_` for compound filenames `hello_world.rs`.
- I can compile the file simply using `rustc file.rs`.
- The `main` function is always the first code executed.
- Macros `!` (Not yet understood).
- Rust uses double quotes `"..."`.

## [01 - Cargo](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html)

Cargo!

### What have learned?

- I learned that the `cargo` is a dependency compiler and generator.
- I can create a new project using `cargo new project_name`.
- A project has a `cargo.toml` which is similar to a `package.json` in node.
- I can use `cargo build` to compile the project.
- Cargo generates a `cargo.lock` for dependency version control.
- I can build and run at the same time using `cargo run`. If there is no change in the code, it just executes the already generated binary, otherwise it compiles and executes.
- I can use `cargo check` as a `dry-run`, it compiles but does not generate executable.
- I can use `cargo build --release` to generate the final version of the project! this command creates a more optimized executable but takes longer to build!

## [02 - First program](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html)

Creating an interactive program with std library!

### What have learned?

- I can import libraries using `use lib::module` or by destructuring `use lib::{ module_a, module_b }`.
- `preludio` is a set of default items that rust brings by default in every project eg `String::new()`.
- The `::` (still no definite definition).
- I can declare a variable using the `let` keyword! By default the values are immutable, but I can use `let mut` to set the value to mutable.
- ...
