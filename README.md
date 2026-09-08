# Homebrew Verification Sandbox

Disposable public tap for Gridctl release publication-order tests.

Test casks must download only assets published by
`gridctl/release-verification-sandbox`. They must not point to official Gridctl
releases or replace the production `gridctl/tap/gridctl` installation.

No cask is provided until the corresponding sandbox release assets have been
verified as publicly available. Tap publication credentials must be restricted
to this repository with Contents read/write access.

This repository is test infrastructure, not a supported Gridctl installation
source. Do not copy production credentials here.
