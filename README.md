# Anbernic H700 RG-xx StockOS Modification

[中文说明](#中文说明) | [English](#english)

---

## English

A community-driven modification toolkit and system upgrade package repository for **Anbernic H700 series** devices running **Stock OS** (RGds / RGdsplus and compatible models).

This repository mainly publishes **system upgrade packages**, along with a graphical launcher, system updater, and software center.

### Features

- **Launcher** – Graphical menu to access System Updater and Software Center.
- **System Updater** – Online version check, multi-mirror speed test (GitHub / GitCode), resume download, MD5 verification, update / append modes, auto-reboot.
- **Software Center** – Browse, search, install, uninstall, and update software. Supports categories, screenshots, icons, install/uninstall scripts.
- **Modification Installer** – Unpacks resources, modifies RetroArch and system configs, sets language/volume/LED, installs selected apps.
- **Multi-firmware attribute support** – Auto-detects `rgdsplus`, `rgds`, and `h700` profiles.

### Supported Devices

| Device | Board ID | Status |
|--------|----------|--------|
| RG ds | RGds | Supported |
| RG dsplus | RGdsplus | Supported |
| H700 (generic) | h700 | Partial / experimental |


### Installation

1. Download the latest release package.
2. Copy the entire program directory to your device.
3. Run `main.py` or start via `update.sh`.
4. Follow the on-screen menu.

> **Important:** Do not place the program in `/mnt/mmc/Roms/APPS`. Use PORTS or the recommended path.

### Building / Releasing Upgrade Packages

Upgrade packages are distributed via GitHub Releases.  
Each release should include:

- `update_info.json` – version, filename, MD5, board-specific files.
- `update.zip` – main update package.
- Optional `info_zh_CN.txt` / `info_en_US.txt` – release notes.

Mirror servers:
- GitHub: `https://github.com/cbepx-me/rgds/releases/download/server/`
- GitCode (China): `https://gitcode.com/cbepx/rgds/releases/download/server/`

### Disclaimer

This is an unofficial community project. Modding your device may void warranties, cause data loss, or brick the device. Use at your own risk. Always back up important data and ensure a stable power supply.

### License

MIT License – see [LICENSE](LICENSE).

### Credits

- Author: cbepx-me (G.R.H)
- Community contributors

---

## 中文说明

这是一个面向 **Anbernic H700 系列**设备（RG ds / RG dsplus 等）的 **Stock OS 魔改工具箱与系统升级包发布仓库**。

主要功能：

- **启动器** – 图形菜单，进入系统更新或软件中心。
- **系统更新** – 在线检查、多镜像测速、断点续传、MD5 校验、update / append 模式、自动重启。
- **软件中心** – 浏览、搜索、安装、卸载、更新软件，支持分类、截图、图标、安装/卸载脚本。
- **魔改安装程序** – 解压资源、修改 RetroArch 与系统配置、设置语言/音量/LED、安装所选应用。
- **多固件属性支持** – 自动识别 `rgdsplus`、`rgds`、`h700`。

支持设备：RG ds、RG dsplus；H700 通用版部分实验性支持。

安装：下载 Release 包，复制到设备，运行 `main.py` 或 `update.sh`。

免责：非官方项目，魔改有风险，请自行承担。

作者：上帝之右手
