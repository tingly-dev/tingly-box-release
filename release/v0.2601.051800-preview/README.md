# Tingly Box Release Artifacts

This repository contains release binaries for Tingly Box, synced automatically from the main repository.

## 📦 Downloads

### CLI Binaries

| Platform | Architecture | Download | Checksum |
|----------|-------------|----------|----------|
| Linux | AMD64 | [Download](tingly-box-linux-amd64.zip) | [SHA256](checksums.txt) |
| macOS | AMD64 (Intel) | [Download](tingly-box-macos-amd64.zip) | [SHA256](checksums.txt) |
| macOS | ARM64 (Apple Silicon) | [Download](tingly-box-macos-arm64.zip) | [SHA256](checksums.txt) |
| Windows | AMD64 | [Download](tingly-box-windows-amd64.zip) | [SHA256](checksums.txt) |

### GUI Applications

| Platform | Architecture | Download |
|----------|-------------|----------|
| macOS | ARM64 (Apple Silicon) | [Download](tingly-box-gui-macos-arm64.zip) |
| Windows | AMD64 | [Download](tingly-box-gui-windows-amd64.zip) |

## 🚀 Quick Install

### Using curl (Linux/macOS)
\`\`\`bash
# Detect platform and download appropriate binary
curl -fsSL https://raw.githubusercontent.com/tingly-dev/tingly-box/main/scripts/install.sh | bash
\`\`\`

### Using PowerShell (Windows)
\`\`\`powershell
irm https://raw.githubusercontent.com/tingly-dev/tingly-box/main/scripts/install.ps1
\`\`\`

## 🌐 CDN Access (jsdelivr)

All files are available via jsDelivr CDN for faster downloads:

\`\`\`
https://cdn.jsdelivr.net/gh/tingly-dev/tingly-box-release@{VERSION}/tingly-box-{PLATFORM}-{ARCH}.zip
\`\`\`

Examples:
- Linux AMD64: \`https://cdn.jsdelivr.net/gh/tingly-dev/tingly-box-release@v1.0.0/tingly-box-linux-amd64.zip\`
- macOS ARM64: \`https://cdn.jsdelivr.net/gh/tingly-dev/tingly-box-release@v1.0.0/tingly-box-macos-arm64.zip\`
- Windows AMD64: \`https://cdn.jsdelivr.net/gh/tingly-dev/tingly-box-release@v1.0.0/tingly-box-windows-amd64.zip\`

For the latest version, use \`@latest\` instead of a specific version tag.

## ✅ Verify Checksums

After downloading, verify the integrity of your download:

\`\`\`bash
# Linux/macOS
sha256sum -c checksums.txt

# Windows (PowerShell)
Get-FileHash tingly-box-*.zip -Algorithm SHA256
\`\`\`

## 📝 Version Information

- **Version**: v0.2601.051800-preview
- **Release Date**: 2026-01-08 14:15:21 UTC
- **Source**: [tingly-dev/tingly-box](https://github.com/tingly-dev/tingly-box)

---
_This repository is automatically updated by GitHub Actions._
