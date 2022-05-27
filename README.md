# Flytta
[![Documentation Status](https://readthedocs.org/projects/flytta/badge/?version=latest)](https://flytta.readthedocs.io/en/latest/?badge=latest)

Flytta is a free and open source animation app built with GTK4.
## Features
- Fast
- Free and open source
- Cross-platform
- Marketplace for plugins (for added ease and efficiency of usage and if the core features arent enough)
- Built-in themes

## Installation
### For Windows
Download the [Windows installer](https://github.com/flyttaorg/flytta/releases/download/v0.1.0/flytta-0.1.0-win.exe), and run it.

### For macOS
Download the [macOS installer](https://github.com/flyttaorg/flytta/releases/download/v0.1.0/flytta-0.1.0-macos.dmg), and run it. If you're using a Mac that has the M1 chip, you can install this version of the installer: [flytta-0.1.0-macos-m1.dmg](https://github.con/flyttaorg/flytta/releases/download/v0.1.0/flytta-0.1.0-macos-m1.dmg).

### For Linux
For Debian/Ubuntu: 
```bash
sudo add-apt-repository ppa:flytta/stable
sudo apt-get update
sudo apt-get install flytta
```
For Fedora/Redhat:
```bash
sudo dnf install flytta
```
For Arch:
```bash
sudo pacman -S flytta
```
Or, you can download the binaries:
[![Linux Installer](https://img.shields.io/badge/install-linux-orange.svg)](https://github.com/flyttaorg/flytta/releases/download/v0.1.0/flytta-0.1.0-linux.tar.gz)
For different architectures (other than x86-64), see [other Linux binaries](https://github.com/flyttaorg/flytta/releases/).

## Development
<!-- ### Compiling from source
To compile from source, you need to install the following dependencies:
- [GTK4](https://www.gtk.org/download/)
- [CMake](https://cmake.org/)
- [Git](https://git-scm.com/)

### Installing the dependencies
On Windows:
To install the dependencies on Windows, you can download the setup files from the sites themselves, so: For GTK4: [GTK4](https://www.gtk.org/download/), For CMake: [CMake](https://cmake.org/download/), For Git: [Git](https://git-scm.com/). Or, you can use winget, Chocolatey, or scoop to install them.

On macOS:
To install the dependencies on macOS, you can download the setup files from the sites themselves, so: For GTK4: [GTK4](https://www.gtk.org/download/), For CMake: [CMake](https://cmake.org/download/), For Git: [Git](https://git-scm.com/). Or, you can use brew to install them.

On Linux:
Now, this process may vary from distribution to distribution. Let's get started with Debian/Ubuntu.
```bash
sudo apt install git cmake gtk+3.0
```
Then we go to Fedora/Redhat:
```bash
sudo dnf install git cmake gtk4
```
Then Arch:
```bash
sudo pacman -S git cmake gtk4
``` -->
### Contributing
Read [CONTRIBUTING.md](CONTRIBUTING.md) for info.

### Documentation
The documentation can be found [here](https://flytta.readthedocs.io/en/latest/).    

## License
This project is licensed under the [GPL-2.0](LICENSE.core) license. Both the documentation and the code for the marketplace are licensed under the [MIT](LICENSE.docs) license.
