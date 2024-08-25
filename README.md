<div align="center">

# asdf-scaffold [![Build](https://github.com/particledecay/asdf-scaffold/actions/workflows/build.yml/badge.svg)](https://github.com/particledecay/asdf-scaffold/actions/workflows/build.yml) [![Lint](https://github.com/particledecay/asdf-scaffold/actions/workflows/lint.yml/badge.svg)](https://github.com/particledecay/asdf-scaffold/actions/workflows/lint.yml)

[scaffold](https://hay-kot.github.io/scaffold/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add scaffold
# or
asdf plugin add scaffold https://github.com/particledecay/asdf-scaffold.git
```

scaffold:

```shell
# Show all installable versions
asdf list-all scaffold

# Install specific version
asdf install scaffold latest

# Set a version globally (on your ~/.tool-versions file)
asdf global scaffold latest

# Now scaffold commands are available
scaffold --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/particledecay/asdf-scaffold/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Joey Espinosa](https://github.com/particledecay/)
