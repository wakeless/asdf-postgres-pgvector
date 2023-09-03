<div align="center">

# asdf-postgres-pgvector [![Build](https://github.com/wakeless/asdf-postgres-pgvector/actions/workflows/build.yml/badge.svg)](https://github.com/wakeless/asdf-postgres-pgvector/actions/workflows/build.yml) [![Lint](https://github.com/wakeless/asdf-postgres-pgvector/actions/workflows/lint.yml/badge.svg)](https://github.com/wakeless/asdf-postgres-pgvector/actions/workflows/lint.yml)

[postgres-pgvector](https://github.com/wakeless/asdf-postgres-pgvector) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add postgres-pgvector
# or
asdf plugin add postgres-pgvector https://github.com/wakeless/asdf-postgres-pgvector.git
```

postgres-pgvector:

```shell
# Show all installable versions
asdf list-all postgres-pgvector

# Install specific version
asdf install postgres-pgvector latest

# Set a version globally (on your ~/.tool-versions file)
asdf global postgres-pgvector latest

# Now postgres-pgvector commands are available
pg_config | rg pgvector
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/wakeless/asdf-postgres-pgvector/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Michael Gall](https://github.com/wakeless/)
