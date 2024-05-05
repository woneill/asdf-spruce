<div align="center">

# asdf-spruce [![Build](https://github.com/woneill/asdf-spruce/actions/workflows/build.yml/badge.svg)](https://github.com/woneill/asdf-spruce/actions/workflows/build.yml) [![Lint](https://github.com/woneill/asdf-spruce/actions/workflows/lint.yml/badge.svg)](https://github.com/woneill/asdf-spruce/actions/workflows/lint.yml)

[spruce](https://github.com/geofffranks/spruce) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add spruce
# or
asdf plugin add spruce https://github.com/woneill/asdf-spruce.git
```

spruce:

```shell
# Show all installable versions
asdf list-all spruce

# Install specific version
asdf install spruce latest

# Set a version globally (on your ~/.tool-versions file)
asdf global spruce latest

# Now spruce commands are available
spruce --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/woneill/asdf-spruce/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bill O'Neill](https://github.com/woneill/)
