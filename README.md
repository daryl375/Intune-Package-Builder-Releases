# Intune Package Builder Releases

This repository is the public distribution channel for **Intune Package Builder**, a Windows desktop application for creating Microsoft Intune deployment packages for printers and applications.

The application source code is maintained in a separate private repository. This repository contains only public release metadata and downloadable build artifacts.

## Download

Open the [Releases](../../releases/latest) page to download the latest version.

Available artifacts may include:

- `IntunePackageBuilder-Setup.exe` — recommended Windows installer.
- `IntunePackageBuilder-Setup.exe.sha256` — SHA-256 checksum for installer verification.
- `Intune-Package-Builder-*-win-x64.zip` — portable Windows build.

## Automatic updates

Installed copies of Intune Package Builder check this public repository for a newer release. Update checks and downloads are anonymous; users do not need a GitHub account or access token.

Before an update is installed, the application verifies the installer's SHA-256 checksum. The installer is then launched with Windows administrator approval.

## Security

- Never download an installer from an unofficial location.
- Verify that the download originates from this repository.
- Compare the installer hash with the published `.sha256` file when performing a manual installation.
- Windows may display a SmartScreen warning until releases are signed with a trusted code-signing certificate and have established reputation.

## Support

This repository is intended for release distribution. Report application issues through the support channel provided by your IT organization.
