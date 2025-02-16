# Linux-updater-toolkit-
tool kit to update linux auto
# Linux Version Checker and Updater Tool

Welcome to the **Linux Version Checker and Updater Tool**! This is a simple yet powerful command-line utility designed to help you check your Linux distribution version, update your system to the latest version, and check if a reboot is required—all in one place. The tool is interactive, user-friendly, and comes with a cool design to make your terminal experience more enjoyable.

---

## Features

- **Check Linux Version**: Quickly identify your current Linux distribution and version.
- **Update System**: Automatically update your system using the appropriate package manager (supports `apt`, `yum`, `dnf`, `zypper`, and `pacman`).
- **Check for Reboot**: Determine if a reboot is required after an update and optionally reboot the system.
- **Interactive Menu**: Navigate through options with ease using a colorful and intuitive menu.
- **Cool Design**: ASCII art banner and colorful output make the tool visually appealing.
- **System-Wide Command**: Install the tool once and use it from anywhere in your terminal.

---

## Supported Distributions

This tool works with the following Linux distributions:
- **Debian/Ubuntu** (uses `apt-get`)
- **RedHat/CentOS** (uses `yum`)
- **Fedora** (uses `dnf`)
- **openSUSE** (uses `zypper`)
- **Arch Linux** (uses `pacman`)

If your distribution uses a different package manager, you can easily extend the script to support it.

---

## Installation

### Step 1: Download the Script

Clone this repository or download the `linux_updater` script directly.

```bash
wget https://raw.githubusercontent.com/your-username/your-repo/main/linux_updater
```

### Step 2: Make the Script Executable

Run the following command to make the script executable:

```bash
chmod +x linux_updater
```

### Step 3: Install System-Wide

Move the script to `/usr/local/bin/` to make it available as a command in your terminal:

```bash
sudo mv linux_updater /usr/local/bin/
```

---

## Usage

Once installed, you can use the tool by simply typing:

```bash
linux_updater
```

### Interactive Menu

When you run the tool, you'll see a colorful menu with the following options:

1. **Check Linux Version**: Displays your current Linux distribution and version.
2. **Update System**: Updates your system to the latest version using the appropriate package manager.
3. **Check for Reboot**: Checks if a reboot is required after an update and prompts you to reboot if necessary.
4. **Exit**: Exits the tool.

---

## Example Output

Here’s what the tool looks like in action:

```
  _      _       _        __   __  ___           _        _ _           
 | |    (_)     | |       \ \ / / |_ _|  _ __   | |_ __ _| | | ___ _ __ 
 | |     _ _ __ | | ______ \ V /   | |  | '_ \  | __/ _\` | | |/ _ \ '__|
 | |___ | | '_ \| ||______| | |    | |  | | | | | || (_| | | |  __/ |   
 |_____|/ | | | |_|       |_|    |___| |_| |_|  \__\__,_|_|_|\___|_|   
     |__/|_|                                                           
================================================================
Welcome to the Linux Version Checker and Updater Tool!
================================================================

Please choose an option:
1. Check Linux Version
2. Update System
3. Check for Reboot
4. Exit
================================================================
Choose an option (1-4): 1

Checking current Linux version...
You are currently using: Ubuntu 22.04.3 LTS
Press Enter to continue...
```

---

## Uninstallation

If you no longer need the tool, you can remove it by deleting the script from `/usr/local/bin/`:

```bash
sudo rm /usr/local/bin/linux_updater
```

---

## Contributing

Contributions are welcome! If you'd like to add support for more distributions, improve the design, or add new features, feel free to open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Support

If you encounter any issues or have suggestions for improvement, please open an issue on the [GitHub repository](https://github.com/your-username/your-repo).

---

Enjoy using the **Linux Version Checker and Updater Tool**! 🚀
