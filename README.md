# Otto releases

This repository distributes closed-beta release metadata and packaged builds for Otto.

## Release manifest

[`manifest.json`](manifest.json) is the machine-readable release record. Its fields identify the release version, download URL, SHA-256 checksum, and release notes. Consumers should use the current manifest rather than copying a version or download URL into documentation.

## Downloads

Packaged builds are published through [GitHub Releases](https://github.com/davidharuni/otto-releases/releases). Verify a downloaded build against the checksum in the manifest before use.

This is a distribution repository for release metadata and assets; it does not contain the full Otto application source.
