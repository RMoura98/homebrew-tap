# RMoura98's Homebrew tap

Homebrew casks for [Yonder](https://github.com/RMoura98/yonder), the free, open-source break reminder.

```sh
brew install --cask rmoura98/tap/yonder
```

That's it: Homebrew adds this tap automatically. Update with `brew upgrade --cask yonder`.

The cask follows Yonder's latest GitHub release; a scheduled workflow checks for new versions every few hours and
updates the version and checksum.

Yonder isn't notarized yet, so the cask clears the macOS quarantine flag after installing so the app opens normally.
