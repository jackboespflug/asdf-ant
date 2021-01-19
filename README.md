<div align="center">

# asdf-ant

![Build](https://github.com/jackboespflug/asdf-ant/workflows/Build/badge.svg)
![Lint](https://github.com/jackboespflug/asdf-ant/workflows/Lint/badge.svg)
[![License](https://img.shields.io/github/license/jackboespflug/asdf-ant?label=License&style=plastic&color=success)](https://github.com/jackboespflug/asdf-ant/blob/master/LICENSE)

[Ant](https://ant.apache.org) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add ant
# or
asdf plugin add https://github.com/jackboespflug/asdf-ant.git
```

ant:

```shell
# Show all installable versions
asdf list-all ant

# Install specific version
asdf install ant latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ant latest

# Now ant commands are available
ant -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jackboespflug/asdf-ant/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jack Boespflug](https://github.com/jackboespflug/)
