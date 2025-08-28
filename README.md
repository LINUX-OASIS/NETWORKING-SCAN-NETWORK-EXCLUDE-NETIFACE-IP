# Scan Network - Exclude Interface IP

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![GitHub issues](https://img.shields.io/github/issues/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP)](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP)](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/pulls)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP)](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/releases)
[![GitHub stars](https.img.shields.io/github/stars/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP?style=social)](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/stargazers)

A powerful Bash script to scan your local network for all connected devices. It intelligently identifies your machine's IP address and excludes it from the final results, giving you a clean list of other devices on your network.

## ✨ Features

*   **✨ Interactive Interface Selection:** A user-friendly `whiptail` menu lets you choose which network interface to scan.
*   **🎯 Multi-Tool Scanning:** Leverages `nmap`, `netdiscover`, and `nbtscan` for comprehensive and reliable device discovery.
*   **🤖 Smart Dependency Handling:** Automatically checks for required tools and prompts to install them if they're missing (on `apt`-based systems).
*   **🧹 Clean Output:** Excludes the IP of the scanning machine from the final list for clarity.
*   **💻 Pure Bash:** A lightweight and portable script for your Linux toolkit.

## ✅ Compatibility

This script is designed for Debian-based Linux distributions that use the `apt` package manager. It has been tested and is known to be compatible with:

*   Debian
*   Ubuntu (and its flavors like Kubuntu, Xubuntu)
*   Linux Mint
*   ...and other Debian derivatives.

## 🛠️ Dependencies

The script requires the following command-line tools:

*   `nmap`
*   `netdiscover`
*   `whiptail`

If any of these dependencies are not found on your system, the script will automatically attempt to install them using `sudo apt install`.

## 🚀 Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP.git
    cd NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP
    ```

2.  **Make the script executable:**
    ```bash
    chmod +x custom-NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP.sh
    ```

3.  **Run the script with sudo:**
    `sudo` is required for dependency installation and for network scanning tools like `netdiscover` to function correctly.
    ```bash
    sudo ./custom-NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP.sh
    ```

4.  **Select your network interface** from the interactive menu and let the scan begin!

## 💬 Contributing

[Pull requests, issues, and suggestions are warmly welcomed!](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/issues)

See `CONTRIBUTING.md` for guidelines.

## 🌐 Links

*   [Issues](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/issues)
*   [Pull requests](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/pulls)
*   [Releases](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/releases)
*   [Wiki](https://github.com/LINUX-OASIS/NETWORKING-SCAN-NETWORK-EXCLUDE-NETIFACE-IP/wiki)

## 🧙‍♂️ Maintainer

*   [LINUX-OASIS](https://github.com/LINUX-OASIS)

## 📜 License

This project is licensed under the **GNU General Public License v3.0**.

See the LICENSE file for details.
