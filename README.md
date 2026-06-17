# AI工具箱 Update Feed

This repository is served by GitHub Pages and provides static Electron updater files for AI工具箱.

## Stable Channel

Upload Windows update files to:

```text
api/r2/deepseek-gui/channels/stable/latest/
```

Required files after a Windows build usually include:

```text
latest.yml
AI工具箱-<version>-win-x64.exe
AI工具箱-<version>-win-x64.exe.blockmap
```

The application checks:

```text
https://ymr79600731-sys.github.io/kun-update-server/api/r2/deepseek-gui/channels/stable/latest/latest.yml
```

## Frontier Channel

Upload test builds to:

```text
api/r2/deepseek-gui/channels/frontier/latest/
```
