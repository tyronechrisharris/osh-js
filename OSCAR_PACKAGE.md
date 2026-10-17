# OSCAR source package

This branch is a minimal, immutable-install candidate for OSCAR Viewer. It contains only the `source/core` tree consumed through `osh-js/source/core/...` imports, plus the project license and documentation.

The source tree is byte-for-byte identical to commit `0d3716dc5f5ce8c310757fd5e1e939231e22fe93` in [earocorn/osh-js pull request 6](https://github.com/earocorn/osh-js/pull/6). That pull request carries the reviewable MQTT MessagePort source changes. This packaging branch removes unused demos and legacy build dependencies; it does not modify the runtime source.

OSCAR pins the archive by commit and npm lockfile integrity. Keep this commit reachable until the upstream project publishes an equivalent durable package.
