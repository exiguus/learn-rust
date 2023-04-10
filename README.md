# Learn Rust

<https://www.rust-lang.org/>

## Topics

- [ ] [Introduction](introduction/README.md)
- [ ] [Testing](testing/README.md)
- [ ] [Crates](crates/README.md)
- [ ] [Cargo](cargo/README.md)

## Installation

with [rustup](https://rustup.rs/):

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Other installation methods are available at <https://forge.rust-lang.org/infra/other-installation-methods.html>.

update:

```bash
rustup update
```

```bash
❯ rustc --version
rustc 1.68.2 (9eb3afe9e 2023-03-27)
```

Visual Studio Code: <https://code.visualstudio.com/docs/languages/rust>

## Build

```bash
rustc src/main.rs
```

Example:

```bash
❯ rustc src/main.rs 

❯ ./main 
Hello, world!
```

## Cargo

### New Project

```bash
cargo new hello
```

Example:

```bash
❯ cargo new print
     Created binary (application) `print` package
```

or

```bash
cargo init print
```

Example:

```bash
❯ cargo init print
     Created binary (application) `print` package
```

### Run

```bash
cargo run
```

Example:

```bash
❯ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/hello`
Hello, world!
```

### Build

```bash
cargo build
```

Example:

```bash
❯ cargo build
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
```

## Resources

- <https://www.rust-lang.org/learn>
- <https://doc.rust-lang.org/rust-by-example/>
- <https://doc.rust-lang.org/book/>
- <https://rust-lang.github.io/async-book/>
- <https://doc.rust-lang.org/cargo/>