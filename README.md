<div align="center">

# asdf-air [![Build](https://github.com/pdemagny/asdf-air/actions/workflows/build.yml/badge.svg)](https://github.com/pdemagny/asdf-air/actions/workflows/build.yml) [![Lint](https://github.com/pdemagny/asdf-air/actions/workflows/lint.yml/badge.svg)](https://github.com/pdemagny/asdf-air/actions/workflows/lint.yml)


[air](https://github.com/cosmtrek/air) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add air
# or
asdf plugin add air https://github.com/pdemagny/asdf-air.git
```

air:

```shell
# Show all installable versions
asdf list-all air

# Install specific version
asdf install air latest

# Set a version globally (on your ~/.tool-versions file)
asdf global air latest

# Now air commands are available
air -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pdemagny/asdf-air/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pierre Demagny](https://github.com/pdemagny/)
