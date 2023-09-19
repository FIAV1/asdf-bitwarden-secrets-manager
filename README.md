<div align="center">

# asdf-secrets-manager [![Build](https://github.com/FIAV1/asdf-secrets-manager/actions/workflows/build.yml/badge.svg)](https://github.com/FIAV1/asdf-secrets-manager/actions/workflows/build.yml) [![Lint](https://github.com/FIAV1/asdf-secrets-manager/actions/workflows/lint.yml/badge.svg)](https://github.com/FIAV1/asdf-secrets-manager/actions/workflows/lint.yml)

[secrets-manager](https://github.com/FIAV1/asdf-secrets-manager) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add secrets-manager
# or
asdf plugin add secrets-manager https://github.com/FIAV1/asdf-secrets-manager.git
```

secrets-manager:

```shell
# Show all installable versions
asdf list-all secrets-manager

# Install specific version
asdf install secrets-manager latest

# Set a version globally (on your ~/.tool-versions file)
asdf global secrets-manager latest

# Now secrets-manager commands are available
secrets-manager --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/FIAV1/asdf-secrets-manager/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Federico Frigo](https://github.com/FIAV1/)
