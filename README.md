# ProChord Releases

Public release feed for **ProChord** and **ProChord Receiver**.

This repository intentionally contains **release artifacts and update metadata only**. The ProChord source code remains in the private development repository.

## Safety rules

- A commit to the development repository does not automatically become a release.
- Only explicitly approved builds may be published here.
- `update-manifest.json` remains `"published": false` until a release has passed testing and is approved.
- Installed apps must continue to work normally when this repository or the internet is unavailable.
- Do not store Apple certificates, API private keys, Sparkle private keys, passwords, or other secrets in this repository.

## Update feed

The stable JSON feed is:

`https://raw.githubusercontent.com/isaachaaland-collab/ProChord-Releases/main/update-manifest.json`

A future Sparkle appcast may live at:

`https://raw.githubusercontent.com/isaachaaland-collab/ProChord-Releases/main/appcast.xml`
