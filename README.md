# ArchTrace
> ArchTrace - Official releases for Windows, macOS, and Linux

[📥 Download Latest Release](https://github.com/ArchTrace/ArchTrace/releases/latest)

---

## ✨ What is ArchTrace?

ArchTrace analyzes your C, C++ and Python projects and draws their call graph: which functions call which, starting from your entry points. Explore large codebases, isolate a function's callers and callees, spot call cycles, and export the result.

---

## 📦 Installation

Replace `X.Y.Z` below with the version you downloaded (e.g. `1.1.0`).

### Windows

#### Option 1: MSI Installer (Recommended)

1. Download `ArchTrace_X.Y.Z_x64_en-US.msi`
2. Double-click the file
3. **Windows will show a warning "Unknown publisher"** → This is normal, the app is not signed with a commercial certificate
4. Click **"More info"** then **"Run anyway"**
5. Follow the installation wizard

#### Option 2: NSIS Installer

1. Download `ArchTrace_X.Y.Z_x64-setup.exe`
2. Same process as Option 1

**Note**: Windows SmartScreen may block the installation because the app doesn't have a commercial code signing certificate. This is normal for applications without expensive commercial certificates.

### macOS

Works on both Apple Silicon and Intel Macs.

#### ⚠️ Important - First Installation

macOS will block the app because it's not notarized by Apple.

1. Download `ArchTrace_X.Y.Z_universal.dmg`
2. Open the DMG and drag ArchTrace to Applications
3. **On first launch**, macOS will say "Cannot be opened"
4. Go to **System Settings** > **Privacy & Security**
5. In the "Security" section, click **"Open Anyway"**
6. ArchTrace will open and work normally after this

**Quick alternative** (command line):

```bash
xattr -cr /Applications/ArchTrace.app
```

### Linux

#### Debian/Ubuntu (.deb)

```bash
wget https://github.com/ArchTrace/ArchTrace/releases/download/vX.Y.Z/ArchTrace_X.Y.Z_amd64.deb
sudo apt install ./ArchTrace_X.Y.Z_amd64.deb
```

#### Fedora/RHEL (.rpm)

```bash
wget https://github.com/ArchTrace/ArchTrace/releases/download/vX.Y.Z/ArchTrace-X.Y.Z-1.x86_64.rpm
sudo dnf install ./ArchTrace-X.Y.Z-1.x86_64.rpm
```

#### Any distribution (AppImage)

```bash
wget https://github.com/ArchTrace/ArchTrace/releases/download/vX.Y.Z/ArchTrace_X.Y.Z_amd64.AppImage
chmod +x ArchTrace_X.Y.Z_amd64.AppImage
./ArchTrace_X.Y.Z_amd64.AppImage
```

---

## 🔄 Automatic Updates

ArchTrace automatically checks for updates on startup and every 6 hours. When an update is available, you'll see a notification to install it with one click.

Updates are **cryptographically signed** to ensure their authenticity.

---

## 🔒 Security

#### Why do Windows/macOS show warnings?

These systems show warnings for apps not signed with commercial certificates (cost: ~$300/year). **This doesn't mean the app is dangerous.**

#### How to verify it's safe?

1. ✅ **Signed updates**: Auto-updater uses cryptographic signatures
2. ✅ **Consistent source**: Only download from official GitHub releases
3. ✅ **Issue tracking**: Report problems on GitHub for transparency

---

## 📞 Support

For questions or issues, please [create a ticket](https://archtrace.dev/contact) or contact us at [support@archtrace.dev](mailto:support@archtrace.dev).

---

## 📄 License

Copyright © 2026 ArchTrace. All rights reserved.

This software is proprietary. You may:

- ✅ Download and use the application for personal or commercial purposes
- ✅ Report issues and suggest features

You may NOT:

- ❌ Redistribute the application or its components
- ❌ Reverse engineer, decompile, or disassemble the software
- ❌ Use the ArchTrace name or branding without permission
