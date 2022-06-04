# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test azure-functions-core-tools https://github.com/daveneeley/asdf-azure-functions-core-tools.git "func --help"
```

Tests are automatically run in GitHub Actions on push and PR.
