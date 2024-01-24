<div align="center">

# asdf-mise-gdal [![Build](https://github.com/deploymentking/asdf-mise-gdal/actions/workflows/build.yml/badge.svg)](https://github.com/deploymentking/asdf-mise-gdal/actions/workflows/build.yml) [![Lint](https://github.com/deploymentking/asdf-mise-gdal/actions/workflows/lint.yml/badge.svg)](https://github.com/deploymentking/asdf-mise-gdal/actions/workflows/lint.yml)

[mise-gdal](https://github.com/deploymentking/mise-gdal) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add mise-gdal
# or
asdf plugin add mise-gdal https://github.com/deploymentking/asdf-mise-gdal.git
```

mise-gdal:

```shell
# Show all installable versions
asdf list-all mise-gdal

# Install specific version
asdf install mise-gdal latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mise-gdal latest

# Now mise-gdal commands are available
mise-gdal --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/deploymentking/asdf-mise-gdal/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Lee Myring](https://github.com/deploymentking/)
