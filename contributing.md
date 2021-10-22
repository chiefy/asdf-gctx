# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test gctx https://github.com/chiefy/asdf-gctx.git "gctx --version"
```

Tests are automatically run in GitHub Actions on push and PR.
