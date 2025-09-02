#   Rust Hello World – Capstone Project Toolkit
Welcome to the **Rust Hello World Toolkit**, created as part of the Moringa AI Capstone Project. This guide helps beginners learn Rust programming with the support of Generative AI tools.

---

##  Project Overview

This is a simple, beginner-friendly "Hello World" application built with **Rust**. The goal is to learn a new programming language by leveraging AI to:
*   Understand syntax and structure
*   Set up a working Rust environment
*    Compile and run basic Rust code
*    Document the entire process for others to follow

---

##  Why Rust?

Rust is a modern, fast, and memory-safe systems programming language. It’s a great alternative to C/C++ with a growing developer community. It’s also used in WebAssembly, embedded systems, and blockchain projects.

---
##  System Requirements
    * OS: Ubuntu Linux
    * Tool/Editor required VS Code
    * package Rustc and Cargo


##  Setup Instructions (Ubuntu Example)

### Install Prerequisites
```
    $sudo apt update && sudo apt upgrade -y
    $sudo apt install -y curl build-essential git

```


* Install Rust(via rustup)

  ```
  $curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh


### Restart terminal or run:

```
    source $HOME/.cargo/env
```
### Verify Installation
```
    $rustc --version
    $cargo --version

```

### Clone the Repository:
* Open Terminal {Ctrl+Alt+T}
```
    $git clone https://github.com/edwinkipchumba/Toolkit-with-GenAI.git
    
```

```
$cd Toolkit-with-GenAI

```
        
### Minimal Working Example
File:   src/main.rs

```
    fn main() {
    println!("Hello, world!");
    }
```

### Run the App

```
    $cargo run
```

### Expected output:
    Hello, world!

### AI Prompts & Learning Reflections
Example Prompts Used
    -"How do set up a Rust Hello World Project on ubuntu?"
    -"Explain the role of cargo.toml in a Rust Project?"
    -"Where is the entrypoint of a Rust program?"

### Common Errors & Fixes
| Error | Couse | Solution |
| :-----------------| :-----------------: | ------------------: |
| cargo:command not found | Rust not installed or PATH not updated | Run source SHOME/.cargo/env |
| error:linking with cc failed | Missing build tools | Install with sudo apt install build-essential |
| error[E0425]: cannot find function 'println' | Typo in code(e.g., printIn! instead of println) | Fix the typo |
| program runs but shows no output | Code missing println! | Add println!("Hello, world"), |


### Reference Resources

*   [Official Rust Book](https://doc.rust-lang.org/book/)
 (Highly recommended for beginners)

*   [Rust Installation Guide](https://www.rust-lang.org/tools/)

*   [Cargo – Rust’s Package Manager](https://doc.rust-lang.org/cargo/)

*   [Rust by Example](https://doc.rust-lang.org/rust-by-example/)

### MIT License
    
    MIT License
    
    Copyright (c) [2025] [Kolem Edwin]
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.


###  Created by
    Kolem Edwin | Moringa School AI Capstone | September 2025
