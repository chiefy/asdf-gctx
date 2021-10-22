<div align="center">

# asdf-gctx [![Build](https://github.com/chiefy/asdf-gctx/actions/workflows/build.yml/badge.svg)](https://github.com/chiefy/asdf-gctx/actions/workflows/build.yml) [![Lint](https://github.com/chiefy/asdf-gctx/actions/workflows/lint.yml/badge.svg)](https://github.com/chiefy/asdf-gctx/actions/workflows/lint.yml)


[gctx](https://github.com/adamrodger/gcloud-ctx) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gctx
# or
asdf plugin add gctx https://github.com/chiefy/asdf-gctx.git
```

gctx:

```shell
# Show all installable versions
asdf list-all gctx

# Install specific version
asdf install gctx latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gctx latest

# Now gctx commands are available
gctx --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chiefy/asdf-gctx/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Christopher Najewicz](https://github.com/chiefy/)
