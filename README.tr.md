<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/insurup-logo-dark.svg"><img src=".github/assets/insurup-logo.svg" alt="InsurUp" width="360"></picture></p>

# InsurGateway Tunnel desktop app `Test`

Bu repoda kaynak kod yoktur, yalnızca InsurUp'ın yayın hattının yayımladığı InsurGateway Tunnel masaüstü uygulaması ön sürüm (pre-release) dosyaları (Windows, macOS, Linux) bulunur.

> [!WARNING]
> Bu ön sürümler InsurUp'ın kendi testleri içindir. Müşteri bilgisayarlarına kurmayın. Kararlı repoyu kullanın: [InsurUp/insurgateway-tunnel-desktop-release](https://github.com/InsurUp/insurgateway-tunnel-desktop-release).

## Bütünlük

Windows güncelleme paketi `igw-tunnel-desktop-win-x64.zip` ile macOS ve Linux güncelleme paketleri (`*-full.nupkg`) bir `.sig` taşır: güncelleyicinin paketi uygulamadan önce doğruladığı ECDSA P-256 imzası. Windows dosyalarında `.sha256` vardır; macOS ve Linux dosyalarında yoktur.

<details>
<summary>SHA-256'yı elle denetle</summary>

Dosyalar aynı klasörde. Özet değerleri aynı olmalıdır.

### Windows

```powershell
(Get-FileHash .\igw-tunnel-user-win-x64-Setup.exe -Algorithm SHA256).Hash
Get-Content .\igw-tunnel-user-win-x64-Setup.exe.sha256
```

</details>

## İletişim

https://www.insurup.com
