# Rustexp

A Rust regular expression editor and tester. It compiles to web assembly and
is served from from GitHub pages (built and deployed by
[a GitHub action](https://github.com/lpil/rustexp/actions)). There's no
server-side component at all!

```sh
# Setup
cargo install --locked trunk
# Or see <https://trunkrs.dev/#install> for other alternatives

# Run dev server
trunk serve

# Run tests
cargo test

# Build binary
trunk build --release
```

Deploy contents of `./dist` to your location of choice.
