# MCreator for ARM64 Linux

MCreator port for ARM64 (aarch64) Linux, tested on Debian under Termux.

> [!WARNING]
> This port works **only on Linux**.
> It has been tested only in Termux and may be unstable. Please report any bugs you find in [Issues](../../issues).

<img width="2712" height="1220" alt="Screenshot_2026-10-10-10-08-58-203_com termux x11" src="https://github.com/user-attachments/assets/2eda0d97-3cf4-4c46-b385-25b920d51989" />

## Available versions

| Version | Java | Release |
|---|---|---|
| MCreator 2026.2 33518 | OpenJDK 25 | Latest |
| MCreator 2025.1 EAP05718 | OpenJDK 21 | Pre-release |

## Installation

### 1. Install Java

For MCreator 2026.2 33518:

```bash
apt install openjdk-25-jdk
```

For MCreator 2025.1 EAP05718:

```bash
apt install openjdk-21-jdk
```

### 2. Install wget

```bash
apt install wget
```

### 3. Download MCreator

MCreator 2026.2 33518:

```bash
wget https://github.com/x19062023-netizen/MCreator-port-arm64/releases/download/Releases/MCreator20262.tar.gz
```

MCreator 2025.1 EAP05718:

```bash
wget https://github.com/x19062023-netizen/MCreator-port-arm64/releases/download/Pre-Release/MCreatorEAP2025105718_new.tar.gz
```

### 4. Extract and run

```bash
tar -xzf MCreator20262.tar.gz
```
