# Simple HTTP Server in RUST

This is my journey on learning RUST building a single thread HTTP Server in RUST.

Some basic functionalities:
- Read and parse client requests. Read path and query string.
- Response static files (html, css, etc).

### How to build?

Run the following command:

```
cargo build
```

### How to run?

By default the server is running on port 8080.

```
cargo run
```

or if you want change the port, run the following command

```
PORT=YOUR_CUSTOM_PORT cargo run
```
