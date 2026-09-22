Zalith Launcher 2 — Local Edition

An unofficial modified build of Zalith Launcher 2 for Android.

This fork restores local/offline account support and provides a prebuilt ARM64-v8a APK.

«[!WARNING]
This is an unofficial modified build and is not affiliated with, endorsed by, or distributed by the original Zalith Launcher 2 developers.»

What is this?

This project is a modified version of Zalith Launcher 2 focused on restoring local/offline account functionality.

The goal of this build is simple:

- Restore the local/offline account option.
- Allow the launcher to create and use local accounts.
- Keep the existing Zalith Launcher 2 interface and launcher functionality.
- Provide a ready-to-install ARM64-v8a APK.

Current status

Feature| Status
Local / Offline accounts| ✅ Supported
Minecraft Java Edition launching| ✅ Supported
ARM64-v8a| ✅ Available
Microsoft accounts| ❌ Not supported
Microsoft OAuth login| ❌ Not configured
Original Zalith Launcher 2 UI| ✅ Retained

Microsoft accounts

Microsoft account login is not supported in this build.

The original project obtains its Microsoft OAuth client ID through its build configuration. This fork does not ship a Microsoft OAuth client ID, so Microsoft authentication is intentionally unavailable.

Do not expect the "Sign in with Microsoft" flow to work in this build.

Download

The latest APK is available in the GitHub Releases section:

"Download the latest release" (../../releases/latest)

Current release:

v2.5.3-local-1

Architecture:

ARM64-v8a ("arm64-v8a")

If Android reports that the APK is incompatible with your device, your device may use a different CPU architecture.

Changes from upstream

This fork currently contains the following changes:

- Restored the local/offline account creation flow.
- Restored the normal account menu when adding an account.
- Restored the normal account menu when launching the game without an existing account.
- Adjusted the launcher build configuration for the development/build environment.
- Includes minor native/build-related modifications required for this build.

The changes are based on the Zalith Launcher 2 source tree.

Screenshots

Screenshots can be added here later.

For example:

docs/
└── screenshots/
    ├── accounts.png
    └── launcher.png

Then reference them with:

![Account screen](docs/screenshots/accounts.png)

Building

Requirements

The upstream project contains its own build requirements and instructions.

For development, clone this repository:

git clone https://github.com/simpicutew/ZalithLauncher2-Local.git
cd ZalithLauncher2-Local

Then open the project with Android Studio and build the Android application.

Architecture

The currently published release is built for:

ARM64-v8a

Other architectures have not been tested as part of the current release.

Development

This repository is primarily maintained as a personal modified build.

Changes are made on top of the upstream Zalith Launcher 2 source code rather than being a completely independent launcher implementation.

Pull requests and issues are welcome, but compatibility with the upstream project should not be assumed.

Credits

This project is based on Zalith Launcher 2.

Original project:

https://github.com/ZalithLauncher/ZalithLauncher2

The original project and its contributors retain their respective copyrights and license notices.

This repository does not claim ownership of the original Zalith Launcher 2 code.

AI-assisted development

Parts of the modifications in this fork were developed with assistance from GPT-5.6 Luna.

AI assistance does not change the copyright or licensing status of the original project.

The repository maintainer is responsible for reviewing, testing, and distributing the resulting modifications.

License

This project contains code derived from Zalith Launcher 2 and is distributed according to the applicable upstream license.

See:

- ""LICENSE"" (LICENSE)
- the original Zalith Launcher 2 repository
- the license notices included with the source code

This modified build is provided without warranty.

Disclaimer

Zalith Launcher 2 — Local Edition is an unofficial modification.

It is not the official Zalith Launcher 2 release.

The name, trademarks, logos, and other intellectual property associated with the upstream project remain the property of their respective owners.

Minecraft is a trademark of Microsoft Corporation. This project is not affiliated with or endorsed by Microsoft.

Reporting problems

Before opening an issue, please check whether the problem is specific to this modified build.

When reporting a problem, include:

- Device model
- Android version
- CPU architecture
- Launcher version
- Steps to reproduce the problem
- Relevant logs or screenshots

Do not include passwords, access tokens, private keys, OAuth credentials, or other sensitive information in issues.

Project status

This is a small unofficial modification of Zalith Launcher 2.

The current priority is keeping the local/offline account workflow functional and providing a usable ARM64-v8a build.

Features from the upstream project may change or break as the upstream codebase evolves.