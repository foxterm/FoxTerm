# FoxTerm

> Fast, private terminal tools — built by an engineer, for engineers.

SSH · VNC · SFTP · Docker · Podman — a high-performance, privacy-first terminal suite for macOS & iOS. Native Swift + Metal, zero telemetry.

## Features

- **SSH terminal** — ed25519, host key verification, 256-color, UTF-8, near-zero latency
- **SFTP file management** — secure transfers with native speed
- **Metal-accelerated VNC** — fluid remote desktop, GPU-rendered
- **Docker & Podman** — visual container management
- **Real-time system telemetry** — CPU, RAM, temperature, network, disk, uptime
- **Native performance** — built with Swift, Metal, and C-native libraries (OpenSSL, libssh, libvncclient). Not an Electron wrapper.
- **Zero telemetry** — no tracking, no analytics, no data collection
- **Hardware-isolated credentials** — private keys stored in Apple Secure Enclave & Keychain
- **Encrypted iCloud sync** — configuration synced across devices via your private iCloud container

## Download

| Platform | Link |
| --- | --- |
| macOS (DMG) | [GitHub Releases](https://github.com/foxterm/FoxTerm/releases/latest/download/FoxTerm.dmg) |
| macOS & iOS/iPadOS | [App Store](https://apps.apple.com/us/app/foxterm/id6760452891) |
| Website | [foxterm.app](https://foxterm.app) |

## Requirements

- macOS 14 (Sonoma) or later
- iOS / iPadOS

## FoxTerm Pro

The free version unlocks every feature — SSH, SFTP, VNC, telemetry, and container management — with a cap on the number of nodes (servers) you can manage. FoxTerm Pro removes the cap for **unlimited nodes**, and a single subscription unlocks both macOS and iOS/iPadOS clients under the same Apple ID.

- **macOS (notarized build)** — activate with a Pro license key (monthly, quarterly, yearly, or lifetime plans), delivered instantly after checkout
- **iOS / iPadOS** — activates automatically with your purchase, no license key required

Buy at [pay.foxterm.app](https://pay.foxterm.app).

## Auto-Updates

- Sparkle-based automatic updates with a signed appcast
- Appcast: <https://foxterm.app/appcast.xml>
- Updates appear under the app menu → **Check for Updates**

## Security

- **Zero telemetry** — connection logs never leave your local environment
- **Secure Enclave** — Apple Keychain & Secure Enclave hardware isolation for private key storage
- **Native crypto** — C-native engines with Ed25519 and modern cipher suites
- **iCloud sync** — configuration synced exclusively through your private, encrypted iCloud container

## Building from source

Requires Xcode and CocoaPods.

```bash
pod install
open FoxTerm.xcworkspace
```

## Support

- Email: [foxterm@icloud.com](mailto:foxterm@icloud.com)
- Website: [foxterm.app](https://foxterm.app)
