# Rust/JS

## Integrating a JS runtime inside a Rust app.

Post from the [Deno](https://deno.com/).

> **Roll your own JavaScript runtime**
>
> > [First](https://deno.com/blog/roll-your-own-javascript-runtime)
> >
> > [Second](https://deno.com/blog/roll-your-own-javascript-runtime-pt2)
> >
> > [Third](https://deno.com/blog/roll-your-own-javascript-runtime-pt3)

Code [roll-your-own-javascript-runtime](https://github.com/denoland/roll-your-own-javascript-runtime)

```
$ cargo --version
cargo 1.78.0 (54d8815d0 2024-03-26)
$ cargo add deno_core
Updating crates.io index
      Adding deno_core v0.280.0 to dependencies
$ cargo add tokio --features=full
Updating crates.io index
      Adding tokio v1.37.0 to dependencies
$ cargo add deno_ast
Updating crates.io index
      Adding deno_ast v0.38.2 to dependencies
$ cargo add deno_core
Updating crates.io index
      Adding deno_core v0.280.0 to dependencies
$ cargo add reqwest
Updating crates.io index
      Adding reqwest v0.12.4 to dependencies
```
