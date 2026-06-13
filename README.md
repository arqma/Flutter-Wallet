# Arqma Wallet — prebuilt releases

Public distribution of **Arqma Wallet** desktop and mobile builds for version **5.1.2**.

- **Wallet FFI:** [ArqTras/FFI](https://github.com/ArqTras/FFI/releases)
- **License:** [MIT](LICENSE)

## Download (5.1.2)

Installers and packages are attached to the [5.1.2 release](https://github.com/arqma/Flutter-Wallet/releases/tag/5.1.2).

| Platform | Files |
|----------|--------|
| **Windows** | `Arqma-Wallet-Flutter-5.1.2-windows-x64.zip`, `Arqma-Wallet-Flutter-5.1.2-windows-x64-Setup.exe` |
| **Linux** | `Arqma-Wallet-Flutter-5.1.2-linux-x64.tar.gz`, `Arqma-Wallet-Flutter-5.1.2-x86_64.AppImage` |
| **macOS (signed)** | `Arqma-Wallet-Flutter-5.1.2-macos-signed.zip`, `Arqma-Wallet-Flutter-5.1.2-macos-signed.dmg` — **Developer ID** signed + **notarized** (preferred) |
| **macOS (unsigned)** | `Arqma-Wallet-Flutter-5.1.2-macos-unsigned.zip`, `Arqma-Wallet-Flutter-5.1.2-macos-unsigned.dmg` — CI adhoc only (when present) |
| **Android** | `Arqma-Wallet-Android-5.1.2.apk`, `Arqma-Wallet-Android-5.1.2.aab` |
| **iOS** | `Arqma-Wallet-Mobile-5.1.2-ios-testflight.ipa` (TestFlight / registered devices) |

Checksum files: `SHA256SUMS-android-5.1.2.txt`, `SHA256SUMS-ios.txt` (when present).

### macOS — signed vs unsigned

- **Signed** (`…-macos-signed.*`): **Developer ID** signed and **notarized** by the ArqTras release maintainer. Preferred for end users; Gatekeeper should accept without extra steps.
- **Unsigned** (`…-macos-unsigned.*`): **GitHub Actions CI** builds with adhoc signature only (not Developer ID). For developers or local re-signing.

If macOS still blocks launch, remove quarantine: `xattr -cr "/Applications/Arqma-Wallet.app"`.

## Privacy & App Store

- [Privacy Policy](docs/PRIVACY_POLICY.md)
- [App Store privacy disclosure](docs/APP_STORE_PRIVACY_DISCLOSURE.md)
- [App Store publication requirements](docs/APP_STORE_PUBLICATION_REQUIREMENTS.md)
- [App Store review information](docs/APP_STORE_REVIEW_INFORMATION.md) — Guideline 2.1 notes, demo restore wallet, Resolution Center replies

## Release notes

See [docs/RELEASE_NOTES-5.1.2.md](docs/RELEASE_NOTES-5.1.2.md) when available.

**Non-custodial wallet.** You control your keys. Verify checksums before install. No warranty.
