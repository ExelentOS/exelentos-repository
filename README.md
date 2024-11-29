# ExelentOS Repository

[![Maintenance](https://img.shields.io/maintenance/yes/2024.svg)]()

Welcome to the **ExelentOS** GitHub repository! This project is part of **ExelentOS**, an Arch Linux-based distribution designed to provide a user-friendly experience for newcomers and experienced users alike. The repository primarily hosts the **x86_64 repository** for the distribution.

---

## Project Overview

ExelentOS is tailored for those seeking a smooth transition to Arch Linux, offering features like:
- Pre-configured **KDE Plasma 6** desktop environment.
- Easy-to-use tools for setup and customization.
- Lightweight yet powerful performance with a focus on usability.

This repository is a crucial part of the ExelentOS ecosystem, containing essential resources for managing packages and the system repository.

---

## Features

- **Arch Linux Base**: Enjoy the power and flexibility of Arch with an accessible twist.
- **Custom Repository**: Hosts packages optimized for ExelentOS users.
- **Streamlined Installation**: Works in conjunction with the ExelentOS Installer.

---

## Installation

To use the packages from this repository:
1. Add the ExelentOS repository to your system's `pacman.conf`:
   ```ini
   [exelentos]
   SigLevel = Optional TrustAll
   Server = https://exelentos.github.io/$repo/os/$arch
2. Synchronize the package database:
    ```
    sudo pacman -Sy
3. Install packages from the ExelentOS repository using ```pacman```
    ```
    sudo pacman -S <package-name>
---

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.

Check Contributing.md for more details.

---

## Acknowledgments

Special thanks to the open-source community and contributors who made this project possible. While development is currently inactive, contributions and forks are encouraged to keep the project alive.

Maintainer Note

This repository is part of a broader ecosystem, including:

- ExelentOS ISO Repository
- ExelentOS Installer
- ExelentOS Welcome App

---

## Final note 

**We look forward to seeing how the community enhances and expands ExelentOS!**

![bg](https://github.com/user-attachments/assets/7aaa0fd0-d0ea-4e77-8667-c1f0ccac2a36)
