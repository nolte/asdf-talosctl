<div align="center">

# asdf-talosctl [![Build](https://github.com/nolte/asdf-talosctl/actions/workflows/build.yml/badge.svg)](https://github.com/nolte/asdf-talosctl/actions/workflows/build.yml) [![Lint](https://github.com/nolte/asdf-talosctl/actions/workflows/lint.yml/badge.svg)](https://github.com/nolte/asdf-talosctl/actions/workflows/lint.yml)


[talosctl](https://www.talos.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add talosctl
# or
asdf plugin add talosctl https://github.com/nolte/asdf-talosctl.git
```

talosctl:

```shell
# Show all installable versions
asdf list-all talosctl

# Install specific version
asdf install talosctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global talosctl latest

# Now talosctl commands are available
talosctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Development

```sh
export ASDF_INSTALL_VERSION=1.3.5
export ASDF_INSTALL_PATH=/tmp/asdf-debug

./bin/download
```

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nolte/asdf-talosctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [nolte](https://github.com/nolte/)
