# Releases

This public repository hosts the official binaries for [Aquanode](https://aquanode.io), a lightweight and secure node implementation designed for modern decentralized networks.

> 🔗 For more information, visit [aquanode.io](https://aquanode.io)

## 📦 Introduction

The AI cloud marketplace that automates GPUs into cloud-ready instances.


---

## 💾 Download

Navigate to the [Releases](https://github.com/aquanode/releases/releases) section to download the latest binaries for your platform:

- Linux (x86_64)
- macOS (Apple Silicon and Intel)
- Windows

Each release includes:
- The binary executable
- A checksum file (`.sha256`)
- (Optional) GPG signature

---

## ⚙️ Installation

After downloading the appropriate binary for your OS:

```bash
# Example for Linux
chmod +x ogre-linux-x86_64
sudo mv ogre-linux-x86_64 /usr/local/bin/ogre
````

Check the installation:

```bash
ogre --version
```

## 🔐 Checksums

To verify binary integrity:

```bash
sha256sum -c aquanode-linux-x86_64.sha256
```

You can also validate signatures if GPG `.asc` files are provided.

---

## 📦 Release Notes

See the [Releases](https://github.com/aquanode/releases/releases) section for version-specific notes, improvements, and bug fixes.

