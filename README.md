# Deyin desktop releases

Public **installers and auto-update manifests** for [Deyin](https://deyin.ai) desktop.

This repository is **not** the application source code. For development, issues, and
contributions, use **[DeYinAI/deyin-desktop](https://github.com/DeYinAI/deyin-desktop)**.

## Download

Pick the latest **[GitHub Release](https://github.com/DeYinAI/deyin-releases/releases/latest)** for your platform:

| Platform | Installer |
| --- | --- |
| Windows | `Deyin-Setup-*.exe` |
| Linux (Debian/Ubuntu) | `deyin-*-amd64.deb` |
| Linux (portable) | `deyin-*-x86_64.AppImage` |

Documentation: [docs.deyin.ai](https://docs.deyin.ai)

## Auto-update

The Deyin desktop app polls this repository for new versions via `electron-updater`.
Update manifests (`latest.yml`, `latest-linux.yml`, `latest-mac.yml`) are published
alongside each release. Releases must be **published** (not draft) for in-app updates to
work.

## License

Installers distributed from this repository are subject to the
**[PolyForm Noncommercial License 1.0.0](LICENSE)**. Commercial use requires a separate
license from Deyin (`hello@deyin.ai`).

The **Deyin** name and logos are protected separately — see
[TRADEMARK.md](https://github.com/DeYinAI/deyin-desktop/blob/main/TRADEMARK.md) in the
source repository.
