# Olakai Homebrew tap

Homebrew formulas for the [Olakai](https://olakai.ai) CLI.

```sh
brew install olakai-ai/tap/olakai        # stable
brew install olakai-ai/tap/olakai-beta   # pre-releases
```

The two formulas install the same `olakai` binary and conflict with each other: install one.

Formulas in `Formula/` are written by the Olakai CLI release workflow. Do not edit them by hand.
Binaries are downloaded from `https://get.olakai.ai/cli/releases/`. Other ways to install: `npm i -g olakai-cli`, or `curl -fsSL https://get.olakai.ai/cli | sh`.
