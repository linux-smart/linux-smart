# Linux Smart

**Linux Smart** is a minimal, intuitively powered, terminal-based Linux distribution.

## Features
- Lightweight and optimized
- Intuitively driven command execution
- WiFi, sound, and essential utilities included
- QEMU/KVM compatibility
- Automated build and deployment

## System Requirements
- x86_64 CPU
- At least 512MB RAM
- 1GB disk space

## Installation
1. Download the latest ISO:
   ```bash
   git clone https://github.com/linux-smart/linux-smart.git
   cd linux-smart/dist

2. Write to USB (optional):
   ```bash
   sudo dd if=linux-smart.iso of=/dev/sdX bs=4M status=progress && sync

3. Boot the ISO using QEMU/KVM:
   ```bash
   ./scripts/test_iso.sh

## Versioning
Linux Smart follows semantic versioning (MAJOR.MINOR.PATCH).
