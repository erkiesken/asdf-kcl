
# asdf-kcl

[kcl](https://github.com/twmb/kcl) plugin for the [asdf version manager](https://asdf-vm.com).

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`.

## Install

Plugin:

```shell
asdf plugin add kcl https://github.com/erkiesken/asdf-kcl.git
```

kcl:

```shell
# Show all installable versions
asdf list-all kcl

# Install specific version
asdf install kcl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kcl latest

# Now kcl commands are available
kcl myconfig list
kcl admin topic list
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

## License

See [LICENSE](LICENSE) © [Erki Esken](https://github.com/erkiesken/)
