# Slow binrw enum magic parsing demo

```sh
cargo run --release
# Elapsed: 131.23725ms

# With `magic` changed to return `Error::NoVariantMatch` instead, which doesn't
# include `Box`
cargo run --release
# Elapsed: 35.870792ms
```
