# Homebrew tap for Scrub

Scrub replaces private details with reversible placeholders before you paste text into an AI, then restores the answer locally. Source: [onurkat/scrub-desktop](https://github.com/onurkat/scrub-desktop).

```sh
brew install onurkat/scrub/scrub-desktop   # menu-bar app, built from source on your Mac
ln -s "$(brew --prefix scrub-desktop)/Scrub.app" /Applications/Scrub.app
brew install onurkat/scrub/scrub           # command-line filter
```

The app is compiled on your machine from the tagged source archive, so it opens without a Gatekeeper prompt; no quarantine flags are removed.
