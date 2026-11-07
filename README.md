# Hodie download

The download page and update feed for Hodie, a personal Android life-tracking app.

- Page: https://junex05.github.io/hodie-download/
- Update feed: `latest.json` (version code, version name, APK address, SHA-256, size)
- APKs: the Releases of this repo, one per version

This repo holds no source code and no keys. Every APK is signed with the same key, so a new version installs over the old one and keeps its data.

Check a download: `sha256sum hodie-<version>.apk` must match `sha256` in `latest.json`.
