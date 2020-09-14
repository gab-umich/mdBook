# Chapter 2

this is chapter 2. loll

## Inserting runnable Rust files

With the following syntax, you can insert runnable Rust files into your book:

```hbs
\{{#playpen file.rs}}
```

The path to the Rust file has to be relative from the current source file.

When play is clicked, the code snippet will be sent to the [Rust Playpen] to be
compiled and run. The result is sent back and displayed directly underneath the
code.

Here is what a rendered code snippet looks like:

{{#playpen example.rs}}

[Rust Playpen]: https://play.rust-lang.org/
