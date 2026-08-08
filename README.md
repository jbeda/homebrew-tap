# homebrew-tap

Homebrew formulae for [jbeda](https://github.com/jbeda)'s tools.

```
brew install jbeda/tap/mdreflow
```

Or tap first, then install by name:

```
brew tap jbeda/tap
brew install mdreflow
```

## Formulae

- [mdreflow](https://github.com/jbeda/mdreflow): reflow Markdown prose, sentence-per-line by default.

## How this repo works

Formulae in `Formula/` are generated and committed by
[goreleaser](https://goreleaser.com/customization/homebrew_formulas/) when a
release is tagged in the source repo; nothing here is edited by hand.
File issues against the tool's own repo, not this one.

## License

Apache-2.0.
