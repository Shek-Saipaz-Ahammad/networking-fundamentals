# 💻 04 - Cisco IOS CLI

## 🎯 Overview

This topic introduces the Cisco IOS Command Line Interface (CLI), different CLI modes, basic configuration commands, and how to save device configurations.

---

## 📚 Topics Covered

### 🖥️ What is a CLI?

A Command Line Interface (CLI) allows users to configure and manage network devices by entering commands.

### 🔌 How to Connect to a Cisco Device

A Cisco device can be accessed through the console port, SSH, or Telnet using a terminal emulator.

### 💻 Terminal Emulator (PuTTY)

PuTTY is a terminal emulator used to connect to Cisco devices through the console, SSH, or Telnet.

### 👤 User EXEC Mode

The first mode after logging in. It allows basic monitoring commands but does not allow configuration changes.

### 🔑 Privileged EXEC Mode

Provides access to advanced monitoring commands and allows entry into configuration mode.

### ⚡ Cisco IOS CLI Shortcuts

CLI shortcuts help execute commands faster and improve productivity while configuring devices.

### ⚙️ Global Configuration Mode

Used to configure the overall settings of a Cisco device.

### 🔒 `enable password`

Sets a basic password for entering Privileged EXEC mode.

### 📄 Running Configuration & Startup Configuration

- **Running Configuration:** The current active configuration stored in RAM.
- **Startup Configuration:** The saved configuration stored in NVRAM and loaded after reboot.

### 💾 Saving the Configuration

The current running configuration can be saved to the startup configuration to preserve changes after a restart.

### 🔐 `service password-encryption`

Encrypts plain-text passwords stored in the configuration file.

### 🛡️ `enable secret`

Sets a secure encrypted password for Privileged EXEC mode. It is more secure than `enable password`.

### ❌ Canceling or Deleting Commands

Configuration commands can be removed using the `no` keyword.
For example:

```text
no hostname
no enable password
```

---

## 🚀 Next Step

The next step is to practice configuring Cisco devices using the IOS CLI and become familiar with common configuration commands.
