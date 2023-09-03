# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test postgres-pgvector https://github.com/wakeless/asdf-postgres-pgvector.git "pg_config | rg pgvector"
```

Tests are automatically run in GitHub Actions on push and PR.
