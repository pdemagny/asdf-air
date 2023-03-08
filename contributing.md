# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test air https://github.com/pdemagny/asdf-air.git "air -v"
```

Tests are automatically run in GitHub Actions on push and PR.
