<div align="center">

# asdf-tf-summarize [![Build](https://github.com/adamcrews/asdf-tf-summarize/actions/workflows/build.yml/badge.svg)](https://github.com/adamcrews/asdf-tf-summarize/actions/workflows/build.yml) [![Lint](https://github.com/adamcrews/asdf-tf-summarize/actions/workflows/lint.yml/badge.svg)](https://github.com/adamcrews/asdf-tf-summarize/actions/workflows/lint.yml)


[tf-summarize](https://github.com/adamcrews/asdf-tf-summarize) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add tf-summarize
# or
asdf plugin add tf-summarize https://github.com/adamcrews/asdf-tf-summarize.git
```

tf-summarize:

```shell
# Show all installable versions
asdf list-all tf-summarize

# Install specific version
asdf install tf-summarize latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tf-summarize latest

# Now tf-summarize commands are available
tf-summarize --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/adamcrews/asdf-tf-summarize/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Adam Crews](https://github.com/adamcrews/)
