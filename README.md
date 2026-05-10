# dimgord's Homebrew Tap

Personal Homebrew tap for tools maintained by [@dimgord](https://github.com/dimgord). Formulae are auto-generated and pushed by [GoReleaser](https://goreleaser.com) on each upstream tag.

## Usage

```sh
brew tap dimgord/tap
```

Then install any of the formulae below.

## Available formulae

| Tool | Upstream | Description |
|---|---|---|
| `sopds-go` | [dimgord/sopds-go](https://github.com/dimgord/sopds-go) | Self-hosted OPDS catalog server (Go rewrite of SOPDS) |

```sh
brew install sopds-go
```

## How it works

This tap holds nothing but auto-generated `Formula/*.rb` files. Each upstream project's `.goreleaser.yaml` has a `brews:` section that, on every `v*` tag push, builds release archives and opens a commit to this repo updating the formula's URL + SHA-256 to point at the new release. No manual formula maintenance.

## Bug reports

For issues with a specific formula, please file at the **upstream** repo (linked in the table above). Tap-level meta-issues (the auto-update workflow itself, or formula drift) → file here.

## License

Each formula references its upstream's license — see the upstream repo. The formula file itself is BSD-2-Clause as a courtesy (matching Homebrew core's convention for formula files).
