# HidHide ARM64 Installer

Builds an ARM64-native HidHide MSI from the official Nefarius installer code and signed ARM64 payloads.

## Output

GitHub Actions produces `HidHide_ARM64_1.7.346.0.msi` as a workflow artifact.

## Payload

- HidHide driver: ARM64 1.6.280.0
- HidHideClient: ARM64 1.7.346.0
- HidHideCLI: ARM64 1.7.346.0
- Installer logic: pinned upstream Nefarius/HidHide source
- nefcon: official ARM64 `nefconw.exe` v1.20.0

Run the **Build HidHide ARM64 MSI** workflow from the Actions tab.
