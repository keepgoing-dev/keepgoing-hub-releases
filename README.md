# KeepGoing Den releases

Notarised macOS builds of [KeepGoing Den](https://keepgoing.dev/den), a menu bar Pomodoro that
keeps one job in front of you. It was called KeepGoing Hub until 0.3.0, and this repository keeps
that name so older versions can still find their updates. The source lives elsewhere; this
repository only carries the releases.

## Install

1. Download `KeepGoing-Den-X.Y.Z.dmg` from the [latest release](https://github.com/keepgoing-dev/keepgoing-hub-releases/releases/latest).
2. Open it and drag **KeepGoing Den** to **Applications**.
3. Open it from Applications. It is signed with a Developer ID and notarised by Apple, so macOS
   opens it without a warning.

Each release carries a `.sha256` beside the DMG. To check a download:

```sh
shasum -a 256 -c KeepGoing-Den-X.Y.Z.dmg.sha256
```

From 0.2.0 on, the app updates itself: it offers each new version in the menu bar and installs it
when you press Install. A KeepGoing Hub install updates to the Den in place and keeps everything.

## Price

Free to use. The Nudge, switching desktops from the notch and more than two bound desktops are
free for 14 days, then need a one-time licence, on up to 3 Macs. See
[keepgoing.dev/den](https://keepgoing.dev/den#price).

## Requirements

macOS 14 or later, on Apple Silicon or Intel (one universal build).

## Bugs and questions

Open an [issue](https://github.com/keepgoing-dev/keepgoing-hub-releases/issues), or write to
[hello@keepgoing.dev](mailto:hello@keepgoing.dev).
