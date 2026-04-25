# Install

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

## macOS

Open the `.dmg` file and move **Blabler Desktop** to **Applications**.

## Windows

Run the `.msi` installer and follow the setup steps.
