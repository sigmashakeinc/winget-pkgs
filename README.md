# winget-pkgs

WinGet manifest for [SigmaShake](https://sigmashake.com) CLI tools.

## Install (once published)

```powershell
winget install SigmaShake.SigmaShake
```

## Publishing

When release binaries are available, submit the manifest as a PR to [microsoft/winget-pkgs](https://github.com/microsoft/winget-pkgs) or use:

```powershell
wingetcreate submit manifests/s/SigmaShake/SigmaShake/0.0.1/
```
