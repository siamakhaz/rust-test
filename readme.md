# Rust sample project
<img align="right" width="100" height="50" src="https://bitbucket.octasic.com:8443/projects/DEVOPS/repos/rust-sample/raw/docs/octasic-logo.png" alt="Image not found" onerror="this.src='http://www.octasic.com/wp-content/themes/Octasic/assets/images/logo.png';"> 


# Table of content
- [Rust sample project](#rust-sample-project)
- [Table of content](#table-of-content)
- [How install Rust](#how-install-rust)
  - [Try Rust online](#try-rust-online)
  - [Install it!](#install-it)
    - [Windows](#windows)
    - [Linux](#linux)
  - [Integrate with VSCode](#integrate-with-vscode)
  - [Cargo](#cargo)
  - [want more?](#want-more)
# How install Rust
<img align="right" width="150" height="150" src="https://bitbucket.octasic.com:8443/projects/DEVOPS/repos/rust-sample/raw/docs/rust-logo.svg" alt="Image not found" onerror="this.src='docs/rust-logo.svg';">
as they say "A language empowering everyone to build reliable and efficient software." 

## Try Rust online
You can try Rust online in the Rust Playground without installing anything on your computer.
<a href="https://play.rust-lang.org/"><button type="button">Try it online</button></a>

## Install it!

### Windows 
you need to donload **[RUSTUP-INIT.EXE](https://static.rust-lang.org/rustup/dist/x86_64-pc-windows-msvc/rustup-init.exe)** and install it on your computer.
### Linux 

If you’re a Windows Subsystem for Linux user or a linux user run the following in your terminal, then follow the on-screen instructions to install Rust.

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

>**for more installation options you can see this [link](https://forge.rust-lang.org/infra/other-installation-methods.html).**

## Integrate with VSCode
<img align="right" width="150" height="100" src="https://bitbucket.octasic.com:8443/projects/DEVOPS/repos/rust-sample/raw/docs/VSCode-logo.png" alt="Image not found" onerror="this.src='docs/VSCode-logo.png';">

you can install **[rust-analyser](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)** extention and you are ready to go.

## Cargo

When you install Rustup you’ll also get the latest stable version of the Rust build tool and package manager, also known as Cargo. Cargo does lots of things:

- build your project with ```cargo build```
- run your project with ```cargo run```
- test your project with ```cargo test```
- build documentation for your project with ```cargo doc```
- publish a library to crates.io with ```cargo publish```

To test that you have Rust and Cargo installed, you can run this in your terminal of choice:
```
cargo --version
```
you should see something like this ```cargo 1.61.0 (a028ae42f 2022-04-29)```

## want more?
if you want to study more you can read **[The Cargo Book](https://doc.rust-lang.org/cargo/index.html)**.

>all the info comefrom [Rust Get start page](https://www.rust-lang.org/learn/get-started)
