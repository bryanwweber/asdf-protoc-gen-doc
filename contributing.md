# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test protoc-gen-doc https://github.com/bryanwweber/asdf-protoc-gen-doc.git "protoc-gen-doc --help"
```

Tests are automatically run in GitHub Actions on push and PR.
