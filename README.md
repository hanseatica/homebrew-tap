# Hanseatica Homebrew tap

Homebrew formulae for [Hanseatica](https://github.com/hanseatica) tools.

## Install

```sh
brew install hanseatica/tap/hanse
```

or, equivalently:

```sh
brew tap hanseatica/tap
brew install hanse
```

## Formulae

| Formula | Description |
| ------- | ----------- |
| `hanse` | Command-line client for [hanse](https://github.com/hanseatica/hanse) — unified positions, balances, and history across brokerage accounts |

## Upgrading

```sh
brew upgrade hanse
```

## How this tap is maintained

The files under `Formula/` are generated and pushed automatically by
[dist](https://github.com/axodotdev/cargo-dist) when a release is tagged in
[hanseatica/hanse](https://github.com/hanseatica/hanse). Don't edit them by
hand — changes belong in that repo's release configuration.

## License

MIT — see [LICENSE](LICENSE).
