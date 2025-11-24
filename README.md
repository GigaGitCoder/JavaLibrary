# Setup

1) Download [Java](https://www.java.com/en/download/?locale=en) from official website.

2) Download [Docker](https://www.docker.com/) from official website and follow the instructions to set it up:
- [Download for Mac – Apple Silicon](https://desktop.docker.com/mac/main/arm64/Docker.dmg?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module)
- [Download for Mac – Intel Chip](https://desktop.docker.com/mac/main/amd64/Docker.dmg?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module)
- [Download for Windows – AMD64](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module)
- [Download for Windows – ARM64](https://desktop.docker.com/win/main/arm64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=module)
- [Download for Linux](https://docs.docker.com/desktop/linux/install/)

# Gitmodules

- [JavaBookService](https://github.com/GigaGitCoder/JavaBookService)
- [JavaUserService](https://github.com/GigaGitCoder/JavaUserService)
- [JavaLibrarySite](https://github.com/GigaGitCoder/JavaLibrarySite)

# Quick Start

- Linux/macOS:

```bash
git clone --recurse-submodules https://github.com/GigaGitCoder/JavaLibrary

cd JavaLibrary

./setup-build.sh

./start.sh
```
`./stop.sh/` для выключения.
  
- Windows:
```cmd
git clone --recurse-submodules https://github.com/GigaGitCoder/JavaLibrary

cd JavaLibrary

start setup-build.ps1

start start.ps1
```
`start stop.ps1` для выключения.
