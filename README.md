# homebrew-tap

Homebrew formulae for Daniel Oh's projects.

```sh
brew install daniel-oh/tap/background-remover
```

| Formula | What it is |
|---|---|
| [`background-remover`](Formula/background-remover.rb) | [Background removal as a small HTTP service](https://github.com/daniel-oh/background-remover): prebuilt binaries for macOS (Apple silicon) and Linux (x86_64, aarch64), plus a `brew services` definition |

The formulae install release binaries; nothing is compiled. Each release of
a project rewrites its formula here from the release's checksums, so the
version in the tap matches the latest tag.

## License

MIT. The projects the formulae install carry their own licences.
