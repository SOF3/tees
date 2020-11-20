# Tees

This is a fork of the `tee` library to support `Seek`.
The following are description taken from the original repo.

A rustlang adapter for readers which delegate read bytes to a writer, adapted from the standard library's `std::io::Read#tee` which has since been deprecated.

## install

Add the following to your `Cargo.toml` file

```toml
[dependencies]
tees = "0.1.1"
```

## examples
```rust
let tee_reader = tee::TeeReader::new(reader, writer);
```

Doug Tangren (softprops) 2015
