# Install

Other platforms:

- **Android**: [Google Play](https://play.google.com/store/apps/details?id=net.robmar.blabler.android&pli=1)
- **iPhone / iPad (test build)**: [TestFlight](https://testflight.apple.com/join/GHcCwDW3)

## Ubuntu / Debian

Choose the package that matches both your system architecture and Ubuntu release:

- `*_amd64_ubuntu22.04.deb` for Ubuntu 22.04 on `x86_64` / `amd64`
- `*_arm64_ubuntu22.04.deb` for Ubuntu 22.04 on `arm64` / `aarch64`
- `*_amd64_ubuntu24.04.deb` for Ubuntu 24.04 on `x86_64` / `amd64`
- `*_arm64_ubuntu24.04.deb` for Ubuntu 24.04 on `arm64` / `aarch64`

Check your architecture with:

```bash
dpkg --print-architecture
```

Check your Ubuntu release with:

```bash
lsb_release -rs
```

Install with:

```bash
sudo apt install ./package-name.deb
```

## Linux AppImage

Choose the file that matches your CPU architecture:

- `*_amd64.AppImage` for `x86_64` / `amd64`
- `*_arm64.AppImage` for `arm64` / `aarch64`

Run it with:

```bash
chmod +x Blabler.AppImage
./Blabler.AppImage
```

## macOS

Open the `.dmg` file and move **Blabler Desktop** to **Applications**.

## Windows

Run the `.msi` installer and follow the setup steps.
