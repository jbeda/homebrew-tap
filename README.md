# homebrew-tap

Homebrew casks for [jbeda](https://github.com/jbeda)'s tools, macOS only.
Linux users: each tool's releases page has prebuilt tarballs, and Go tools
install with `go install`.

```
brew install jbeda/tap/mdreflow
```

Or tap first, then install by name:

```
brew tap jbeda/tap
brew install mdreflow
```

## Casks

- [mdreflow](https://github.com/jbeda/mdreflow): reflow Markdown prose, sentence-per-line by default.

## How this repo works

Casks in `Casks/` are generated and committed by
[goreleaser](https://goreleaser.com/customization/homebrew_casks/) when a
release is tagged in the source repo; nothing here is edited by hand.
File issues against the tool's own repo, not this one.

This repo previously hosted the (long-archived) ksonnet tap; those contents
are retired and live only in the git history.

## License

Apache-2.0.
