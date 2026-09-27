# Euthymia releases

This public repository hosts downloadable Euthymia binaries. The application
source remains private in `zendeus/euthymia`.

Linux Wayland packages are available for x86-64 and ARM64 as AppImage, `.deb`,
`.rpm`, and `.tar.zst` files, with matching SHA-256 checksums and per-architecture
JSON manifests.

New releases publish an aggregate `release.json` alongside their downloadable
assets. It records the release tag, source revision, prerelease status, and
version-specific URLs and SHA-256 hashes for every architecture and format.
Release metadata lives in release assets; CI does not commit update pointers
to this repository. Earlier previews through rc.3 have per-architecture
manifests only.

The website can read the [latest stable release API](https://api.github.com/repos/zendeus/euthymia-releases/releases/latest)
and use each asset's `browser_download_url` for direct GitHub downloads.
Prereleases appear in the [releases list API](https://api.github.com/repos/zendeus/euthymia-releases/releases).
The latest stable endpoint will return no release until one is published.
