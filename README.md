<div align="center">

# asdf-envs [![Build](https://github.com/longdog/asdf-envs/actions/workflows/build.yml/badge.svg)](https://github.com/longdog/asdf-envs/actions/workflows/build.yml) [![Lint](https://github.com/longdog/asdf-envs/actions/workflows/lint.yml/badge.svg)](https://github.com/longdog/asdf-envs/actions/workflows/lint.yml)

[envs](https://github.com/longdog/envs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add envs
# or
asdf plugin add envs https://github.com/longdog/asdf-envs.git
```

envs:

```shell
# Show all installable versions
asdf list-all envs

# Install specific version
asdf install envs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global envs latest

# Now envs commands are available
envs --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/longdog/asdf-envs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Denis Abrosimov](https://github.com/longdog/)
