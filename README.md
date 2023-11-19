# htmx / askama + axum on Shuttle

An experiment with [htmx] and [askama] served with axum using Shuttle.

```shell
cargo shuttle run
```

## Server-Sent Events

Visit `http://127.0.0.1:8000/stream` to see a stream of server-sent events.

[askama]: https://docs.rs/askama/0.12.1/askama/
[htmx]: https://htmx.org/

## Sources & Further reading

See [htmx, Rust & Shuttle: A New Rapid Prototyping Stack] by Joshua Mo, the blog post that inspired this experiment.

[htmx, Rust & Shuttle: A New Rapid Prototyping Stack]: https://www.shuttle.rs/blog/2023/10/25/htmx-with-rust
