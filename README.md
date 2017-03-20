# cargo-test-xunit
Converts cargo test output into a xunit report

## Install

```
cargo install --git https://github.com/evernym/cargo-test-xunit
```

## Run
cargo test-xunit

After executing this command in root directory of project will be created file `test-results.xml`
containing `cargo test` output in xunit format.