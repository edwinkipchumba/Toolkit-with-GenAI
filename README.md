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

    * Prompt used:
-Link to the curriculum for the prompt:https://ai.moringaschool.com/ai-software/ai-use-cases/usecases-documentation/
-Prompt 2: Intent and Logic Explanation

### Example Prompts Used
-Prompt 2: Intent and Logic Explanation
I need help documenting this capstone project, which will harness the power of generative AI prompts to explore and learn a new technology in software development. which will create a beginner-friendly toolkit that helps anyone get started with that technology.The intent and logic behind this code. Please:
[Rust]
[hello world]
 Toolkit Document (Markdown or PDF) including: 
 . Overview of the chosen tech. 
 . Set up instructions. 
 . Minimal working example (Hello World, quick API call, etc.). 
 . AI prompts used and your learning reflections. :: add this as documentation reference 
 . Common errors & how to resolve them. 
 . Reference resources (official docs, tutorials).

### Reflections
* Generative AI was helpful in breaking down new concepts (e.g., Cargo, main.rs).
* It provided step-by-step troubleshooting when errors occurred.
* The key learning was that asking precise questions yields the most useful results.

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
https://github.com/edwinkipchumba/Toolkit-with-GenAI/blob/main/LICENSE  
   