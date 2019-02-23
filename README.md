# Rust Hello Web Server

This is a tiny example to build the web server with Rust from Rust Book.

## Usage

### Run server

```shell
$ cargo run
```

### Try to connect to `http://127.0.0.1:7878`

- `/` : response `Hello.html`
- `/sleep` : response `Hello.html` after 5 sec.
- other routes : response `404.html`
