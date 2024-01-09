<div align="center">

# asdf-protoc-gen-doc [![Build](https://github.com/bryanwweber/asdf-protoc-gen-doc/actions/workflows/build.yml/badge.svg)](https://github.com/bryanwweber/asdf-protoc-gen-doc/actions/workflows/build.yml) [![Lint](https://github.com/bryanwweber/asdf-protoc-gen-doc/actions/workflows/lint.yml/badge.svg)](https://github.com/bryanwweber/asdf-protoc-gen-doc/actions/workflows/lint.yml)

[protoc-gen-doc](pseudomuto/protoc-gen-doc) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add protoc-gen-doc
# or
asdf plugin add protoc-gen-doc https://github.com/bryanwweber/asdf-protoc-gen-doc.git
```

protoc-gen-doc:

```shell
# Show all installable versions
asdf list-all protoc-gen-doc

# Install specific version
asdf install protoc-gen-doc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc-gen-doc latest

# Now protoc-gen-doc commands are available
protoc-gen-doc --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bryanwweber/asdf-protoc-gen-doc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bryan Weber](https://github.com/bryanwweber/)
