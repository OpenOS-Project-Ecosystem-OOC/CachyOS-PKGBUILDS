<div align="center">
  <img src="https://github.com/CachyOS/calamares-config/blob/grub-3.2/etc/calamares/branding/cachyos/logo.png" width="64" alt="CachyOS logo"></img>
  <br/>
  <h1 align="center">CachyOS</h1>
</div>

# CachyOS PKGBUILDS

[![AI agent ready](https://img.shields.io/badge/AI_agent-ready-2ea44f?style=flat-square)](https://github.com/Interested-Deving-1896/fork-sync-all/blob/main/DOCS/ai-agent-badges.md)
[![Open in Codex](https://img.shields.io/badge/Open_in-Codex-000000?style=flat-square&logo=openai&logoColor=white)](https://chatgpt.com/codex)
[![Open in Claude Code](https://img.shields.io/badge/Open_in-Claude_Code-d97757?style=flat-square&logo=anthropic&logoColor=white)](https://claude.ai/code)
[![Open in GitHub Copilot](https://img.shields.io/badge/Open_in-GitHub_Copilot-181717?style=flat-square&logo=githubcopilot&logoColor=white)](https://github.com/copilot)
[![Open in Cursor](https://img.shields.io/badge/Open_in-Cursor-111111?style=flat-square)](https://cursor.com/agents)
[![Use with Gemini CLI](https://img.shields.io/badge/Use_with-Gemini_CLI-4285f4?style=flat-square&logo=googlegemini&logoColor=white)](https://github.com/google-gemini/gemini-cli)
[![KDE Eco](https://img.shields.io/badge/KDE%20Eco-certified-brightgreen?logo=kde&logoColor=white&style=flat-square)](https://eco.kde.org/) [![Blue Angel](https://img.shields.io/badge/Blue%20Angel-DE--UZ%20215-0055a4?style=flat-square)](https://www.blauer-engel.de/en/certification/criteria)

[CachyOS](https://cachyos.org/) PKGBUILDS is a collection of [PKGBUILD](https://wiki.archlinux.org/index.php/PKGBUILD) scripts for building and installing packages on any Arch Linux-based operating system.

## Prerequisites

In order to use these PKGBUILD scripts, you will need to have the following tools and libraries installed on your system:

- [Git](https://git-scm.com/)
- [make](https://www.gnu.org/software/make/)
- [gcc](https://gcc.gnu.org/)
- [binutils](https://www.gnu.org/software/binutils/)
- [fakeroot](https://wiki.archlinux.org/index.php/Fakeroot)

## Usage

To build and install a package using one of the PKGBUILD scripts in this repository, follow these steps:

1. Clone this repository: `git clone https://github.com/CachyOS/cachyos-pkgbuilds.git`
2. Navigate to the directory of the PKGBUILD script you want to use: `cd cachyos-pkgbuilds/<package>`
3. Build the package: `makepkg -si`
4. Install the package: `sudo pacman -U <packagename>.pkg.tar.zst`

## Contributions

If you would like to contribute to CachyOS PKGBUILDS, please fork this repository and submit a pull request with your changes. Please be sure to follow the [ArchLinux Packaging Guidelines](https://wiki.archlinux.org/title/Arch_package_guidelines) when creating or modifying PKGBUILD scripts.
