# terminal-link

> Create clickable links inside your terminal.

## Usage

```rust
use terminal_link::Link;

fn main() {
    let link = Link::new("DuckDuckGo", "https://duckduckgo.com");
    println!("{}", link);
}
```

## Supported terminals

As of now, the terminals listed in [this Gist](https://gist.github.com/egmontkob/eb114294efbcd5adb1944c9f3cb5feda) have support for clickable links.

## Shortcomings

The library does not do any runtime-checks to determine if a terminal actually supports clickable links. This will be implemented in a later release.

#### License

<sup>
Licensed under either of <a href="license-apache">Apache License, Version
2.0</a> or <a href="license-mit">MIT license</a> at your option.
</sup>

<br>

<sub>
Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
</sub>
