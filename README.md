# cargo-test-xunit
Converts cargo test output into a xunit report

## No maintenance warning

```diff
- We stopped to use and support this project. If you think it is usefull the best way to proceed is forking.
```

## Install

```sh
cargo install --git https://github.com/DSRCorporation/cargo-test-xunit
```

## Run
```sh
cargo test-xunit [-outd path/to/output/dir] [-outf filename]
```

After executing this command in provided directory (or `root` directory by default) of project will be created file with the given filename (or `test-results.xml` by default)
containing `cargo test` output in xunit format.
