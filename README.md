# 🦀 Hello World (Rust)

A simple **Hello World** project built using Rust and Cargo.

---

## 📦 Project Structure

```
hello-world/
├── Cargo.toml
└── src/
    └── main.rs
```

---

## 🚀 Getting Started

### 1. Prerequisites

Make sure Rust is installed:

```bash
rustc --version
cargo --version
```

---

### 2. Clone or Create Project

Create a new project using Cargo:

```bash
cargo new hello-world
cd hello-world
```

---

## ▶️ Run the Project

### Run in development mode

```bash
cargo run
```

Output:

```
Hello, Gautam Nayak! Welcome to the Rust Programming.
```

---

### Run in release mode (optimized)

```bash
cargo run --release
```

---

## 🔨 Build the Project

### Debug build

```bash
cargo build
```

### Release build

```bash
cargo build --release
```

Binary will be generated in:

```
target/release/
```

---

## ▶️ Run Compiled Binary

```bash
./target/release/hello-world
```

(On Windows: `hello-world.exe`)

---

## 📝 Source Code

```rust
fn main() {
    let fname: &str = "Gautam";
    let lname: &str = "Nayak";
    println!("Hello, {} {}! Welcome to the Rust Programming.", fname, lname);
}

```

---

## 🧠 Notes

* `cargo run` compiles and runs the code in one step
* `--release` enables optimizations for better performance
* Cargo manages dependencies and builds automatically

---

## 📚 Learn More

* https://www.rust-lang.org/learn
* https://doc.rust-lang.org/book/

---

## ✨ Author

Gautam Nayak
