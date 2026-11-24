[🇹🇷 TR](./README.tr.md)

<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/insurup-logo-dark.svg"><img src=".github/assets/insurup-logo.svg" alt="InsurUp" width="360"></picture></p>

# InsurGateway Tunnel desktop app `Test`

This repository holds no source code, only the InsurGateway Tunnel desktop app pre-release files (Windows, macOS, Linux) that InsurUp's release pipeline publishes.

> [!WARNING]
> These pre-releases are for InsurUp's own testing. Do not install them on customer machines. Use the stable repository: [InsurUp/insurgateway-tunnel-desktop-release](https://github.com/InsurUp/insurgateway-tunnel-desktop-release).

## Integrity

The Windows update package `igw-tunnel-desktop-win-x64.zip` and the macOS and Linux update packages (`*-full.nupkg`) carry a `.sig`, an ECDSA P-256 signature that the updater verifies before it applies a package. Windows files have a `.sha256`; macOS and Linux files have none.

<details>
<summary>Check the SHA-256 by hand</summary>

Files in the same folder. The hash values must match.

### Windows

```powershell
(Get-FileHash .\igw-tunnel-user-win-x64-Setup.exe -Algorithm SHA256).Hash
Get-Content .\igw-tunnel-user-win-x64-Setup.exe.sha256
```

</details>

## Contact

https://www.insurup.com
