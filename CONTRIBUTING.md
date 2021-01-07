# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test ant https://github.com/jackboespflug/asdf-ant.git --asdf-plugin-gitref main "ant -version"
```

Tests are automatically run in GitHub Actions on push and PR.
