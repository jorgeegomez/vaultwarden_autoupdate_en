# 🔐 Vaultwarden Auto-Update Script

A fully automated Bash script to update [Vaultwarden](https://github.com/dani-garcia/vaultwarden) and its Web UI, including system updates, binary/WebUI backup, and email notifications.
Does not work for Docker Installations!

## 📦 Features

- 🔄 Automatically fetches and builds the **latest Vaultwarden binary**
- 🌐 Automatically downloads and installs the **latest Web UI**
- ✅ Checks required packages: `curl`, `cargo`, `git`, `wget`, `sendmail`
- 💾 Creates backups of the current Vaultwarden binary and Web UI
- 🧹 Cleans up temp files after update

## 🧰 Requirements

- Debian/Ubuntu system with `systemd`
- Root permissions
- Required tools installed:
  - `curl`, `cargo`, `git`, `wget`

## 📥 Installation

Clone this repository:

```bash
git clone https://github.com/svn-josh/vaultwarden_autoupdate.git
cd vaultwarden_autoupdate
chmod +x vaultwarden_update.sh
```

## 🚀 Usage
```bash
sudo ./vaultwarden_update.sh
```

## 📄 License
MIT License – Use at your own risk. This script is not officially affiliated with the Vaultwarden project.
