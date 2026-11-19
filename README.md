# Browser settings bridge

This repository hosts only a static browser-local settings bridge and minimal
information about it. No application source code, build files, binaries,
releases, or application development history are published here.

- Endpoint: [bridge.html](bridge.html)
- GitHub Pages: https://wtfseanscool.github.io/deadlock-shop-upgrades/bridge.html

The embedded-browser page reads and writes settings in that browser's own
`localStorage`. No settings are transmitted to GitHub or a remote storage API.
The website must be reachable over HTTPS for the bridge to initialize.

See [ATTRIBUTION.md](ATTRIBUTION.md) and [LICENSE](LICENSE) for the transport
technique's attribution and license.