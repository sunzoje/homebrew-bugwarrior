# homebrew-bugwarrior

To install [Bugwarrior](https://github.com/ralphbean/bugwarrior) using Homebrew:

```bash
$ brew tap sunzoje/bugwarrior
$ brew install sunzoje/bugwarrior/bugwarrior
```

You can confirm that the installation worked using:

```bash
$ bugwarrior-pull --help
Usage: bugwarrior-pull [OPTIONS]

  Pull down tasks from forges and add them to your taskwarrior tasks.

  Relies on configuration in bugwarriorrc

Options:
  --dry-run
  --flavor TEXT  The flavor to use
  --interactive
  --debug        Do not use multiprocessing (which breaks pdb).
  --help         Show this message and exit.
```
