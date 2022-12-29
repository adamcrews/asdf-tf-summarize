# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test tf-summarize https://github.com/adamcrews/asdf-tf-summarize.git "tf-summarize --help"
```

Tests are automatically run in GitHub Actions on push and PR.
