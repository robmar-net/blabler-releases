# Blabler Desktop Releases

This repository publishes public release assets for **Blabler Desktop**.

## What is here

- Linux packages: `.deb` for Ubuntu 22.04 and 24.04 on `amd64` and `arm64`
- macOS package: `.dmg`
- Windows package: `.msi`
- `SHA256SUMS.txt` for release asset verification

## Support level

- **Linux** is the primary supported platform
- **macOS** and **Windows** builds may be published when they remain inexpensive to maintain

## Notes

- Release assets are published from a private source repository
- Public releases contain distributable artifacts only, not source code or internal project files
- If a platform build is marked experimental in release notes, prefer Linux for the most stable path
- Linux package filenames include both architecture and Ubuntu series so you can choose the matching installer
