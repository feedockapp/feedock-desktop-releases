# Feedock Desktop — Releases

Signed, notarized **macOS build artifacts** and the auto-update manifest
(`latest.json`) for the [Feedock](https://feedock.com) desktop app.

> **This repository contains no source code.** It hosts only the compiled
> installers (`.dmg`, `.app.tar.gz`) and their minisign signatures, published
> automatically by the release CI in the private source repository. The desktop
> app's built-in updater fetches `releases/latest/download/latest.json` from here.

Integrity is guaranteed by the **minisign signature** (the app rejects anything not
signed by Feedock's key) and **Apple notarization** — not by repository privacy.

**Install / update:** see the latest entry under **Releases**.