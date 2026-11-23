# Dubplate Homebrew tap

Install the Dubplate desktop app on an Apple Silicon Mac.

```sh
brew tap lvndry/dubplate
brew trust lvndry/dubplate
brew install --cask dubplate
```

If your Homebrew version does not have the `trust` command, skip that line.
Install the command line tool with `brew install --formula dubplate`.

See the [Dubplate repository](https://github.com/lvndry/dubplate) for documentation and release notes.

## Updating the tap

The **Update Dubplate packages** workflow checks for a new stable release daily.
Run it from this repository’s **Actions** tab to update the tap immediately after
a release. It loads the generator from the commit behind the release tag and
checks both downloads against the published SHA-256 checksums before updating
the cask and formula.
