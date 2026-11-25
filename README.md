# Backshift for macOS

Backshift fixes text typed in the wrong keyboard layout — `ghbdtn` → `привет`, `ghbdsn` →
`привіт`, `руддщ` → `hello` — for English, Russian and Ukrainian at the same time. It also
remembers the layout for each chat, tab and document and selects it when you go there.

## Install

1. Download the latest `Backshift-<version>.dmg` from [Releases](../../releases/latest).
2. Open it and drag Backshift to Applications.
3. Launch Backshift and allow it in System Settings → Privacy & Security → Accessibility. The
   first screen walks you through it.

Requires macOS 13 or later. The app is signed and notarized by UNIBRIXGLOBAL LIMITED.

## Updates

Backshift asks, on its second launch, whether it may check for updates automatically. If you
agree, once a day it reads `appcast.xml` from this repository, and nothing else: no account, no
telemetry, nothing about you or what you type. Updates are signed; Backshift installs only a
version signed with its own key. You can turn the check off in Settings → About, and an
organization can switch it off for everyone with the managed key `SUEnableAutomaticChecks`.

## Privacy

Backshift never stores, logs or sends what you type. The update check above is the only
connection it ever makes.

This repository holds releases and the update feed only.
