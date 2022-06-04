<div align="center">

# asdf-azure-functions-core-tools [![Build](https://github.com/daveneeley/asdf-azure-functions-core-tools/actions/workflows/build.yml/badge.svg)](https://github.com/daveneeley/asdf-azure-functions-core-tools/actions/workflows/build.yml) [![Lint](https://github.com/daveneeley/asdf-azure-functions-core-tools/actions/workflows/lint.yml/badge.svg)](https://github.com/daveneeley/asdf-azure-functions-core-tools/actions/workflows/lint.yml)


[azure-functions-core-tools](https://github.com/daveneeley/asdf-azure-functions-core-tools) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add azure-functions-core-tools
# or
asdf plugin add azure-functions-core-tools https://github.com/daveneeley/asdf-azure-functions-core-tools.git
```

azure-functions-core-tools:

```shell
# Show all installable versions
asdf list-all azure-functions-core-tools

# Install specific version
asdf install azure-functions-core-tools latest

# Set a version globally (on your ~/.tool-versions file)
asdf global azure-functions-core-tools latest

# Now azure-functions-core-tools commands are available
func --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/daveneeley/asdf-azure-functions-core-tools/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dave Neeley](https://github.com/daveneeley/)
