# KeepGoing Hub releases

Notarised macOS builds of the [KeepGoing Hub](https://keepgoing.dev/hub), a menu bar Pomodoro
that keeps one job in front of you. The source lives elsewhere; this repository only carries the
releases.

## Install

1. Download `KeepGoing-Hub-X.Y.Z.dmg` from the [latest release](https://github.com/keepgoing-dev/keepgoing-hub-releases/releases/latest).
2. Open it and drag **KeepGoing Hub** to **Applications**.
3. Open it from Applications. It is signed with a Developer ID and notarised by Apple, so macOS
   opens it without a warning.

Each release carries a `.sha256` beside the DMG. To check a download:

```sh
shasum -a 256 -c KeepGoing-Hub-X.Y.Z.dmg.sha256
```

There is no updater yet: a newer version is installed by downloading the DMG again.

## Requirements

macOS on Apple Silicon or Intel (one universal build).

## Bugs and questions

Open an [issue](https://github.com/keepgoing-dev/keepgoing-hub-releases/issues), or write to
[hello@keepgoing.dev](mailto:hello@keepgoing.dev).
