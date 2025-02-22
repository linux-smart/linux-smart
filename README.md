# Linux Smart

**Linux Smart** is a minimal, AI-powered, terminal-based Linux distribution. It integrates **HuggingFace AI** for natural language processing in the shell.

## Features
- Lightweight and optimized
- AI-driven command execution
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

### **Installation Guide**  

**File:** `INSTALL.md`  
**Location:** `~/linux-smart/docs/INSTALL.md`  

```markdown
# Installation Guide for Linux Smart

## System Requirements
- x86_64 CPU
- At least 512MB RAM
- 1GB disk space

## Building from Source
   ```bash
   git clone https://github.com/linux-smart/linux-smart.git
   cd linux-smart
   ./scripts/build_iso.sh

### **Running in QEMU/KVM**
   ```bash
   ./scripts/test_iso.sh

### **Writing to USB**
   ```bash
   sudo dd if=dist/linux-smart-os.iso of=/dev/sdX bs=4M status=progress && sync
