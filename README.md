# Linux Smart

**Linux Smart** is a minimal, intuitively powered, terminal-based Linux distribution. It integrates **HuggingFace** for natural language processing in the shell.

## Features
- Lightweight and optimized
- Intuitively driven command execution
- WiFi, sound, and essential utilities included
- QEMU/KVM compatibility
- Automated build and deployment

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
Linux Smart OS follows semantic versioning (MAJOR.MINOR.PATCH).
