# Intune Package Builder v1.0.1

Source revision: `7ba2cbfd3dda0bbf36ba25dbf77dad4fac41cf20`

## Included artifact

- `Intune-Package-Builder-v1.0.1-win-x64-framework-dependent.zip`
- Matching SHA-256 checksum file

This portable build requires the .NET 8 Desktop Runtime for Windows x64.

## Important

This folder does not contain the Windows installer. Do not rename the portable executable or ZIP to `IntunePackageBuilder-Setup.exe`; the automatic updater expects a real installer with silent-update support.

For the production release, install Inno Setup 6, build `installer/IntunePackageBuilder.iss`, and upload the resulting installer and checksum as GitHub Release assets.
