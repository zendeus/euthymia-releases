# Euthymia releases

This public repository hosts downloadable Euthymia binaries. The application
source remains private in `zendeus/euthymia`.

There is no production release yet. The first candidate is a Wayland Linux
x86-64 portable archive. Each published candidate will include a `.tar.zst`
archive, a `.sha256` checksum, and a JSON manifest with the version, source
revision, architecture, and archive hash. ARM and X11 builds are not currently
available. NixOS uses a native Nix package; a public binary-based Nix
installation route is planned.

The website can read the [latest stable release API](https://api.github.com/repos/zendeus/euthymia-releases/releases/latest)
and use each asset's `browser_download_url` for direct GitHub downloads.
Prereleases appear in the [releases list API](https://api.github.com/repos/zendeus/euthymia-releases/releases).
The latest stable endpoint will return no release until one is published.
