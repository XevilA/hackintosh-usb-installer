# Hackintosh USB Installer

![Hackintosh USB Installer](https://www.apple.com/newsroom/images/product/os/macos/standard/Apple_macOS-Monterey_Safari-Tab-Groups_10252021_big.jpg.medium.jpg)

## Overview

This application helps you create a Hackintosh USB installer by downloading macOS raw disk images and writing them to a USB device. It provides a simple user interface to select the macOS version, download the image file, and create the USB installer.

## Features

- **Select macOS Version**: Choose between macOS Big Sur, macOS Monterey, or macOS Ventura.
- **Download macOS Image**: Download the selected macOS version's raw disk image from the provided URLs.
- **Create USB Installer**: Write the downloaded image file to a selected USB device to create a Hackintosh installer.

## Screenshots

![Select macOS Version](hackintosh2.png)

![Download Progress](hackintosh3.png)

## Requirements

- Python 3.6 or higher
- PyQt6 library
- Internet connection (for downloading macOS images)
- `diskutil` command-line tool (for formatting USB)

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/XevilA/hackintosh-usb-installer.git]
   cd hackintosh-usb-installer
