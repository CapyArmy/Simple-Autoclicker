# 🖱️ Professional AutoClicker Suite

A high-performance, lightweight automation utility designed for precision and speed. This repository features the standalone Windows executable and the source configurations used to build it for Windows 11.

## 📂 Features

### 1. High-Speed AutoClicker (`autoclicker.exe`)
A robust interaction tool built for efficiency and low-latency performance.
* **Optimized for Windows 11:** Fully compatible with the latest Windows environment.
* **Stable Core:** Built using `bpyreadline3` and `importlib_metadata` for smooth background processing.
* **Portable:** installation required—just download and run the executable.

### 2. Deployment Details
* **Cross-Platform Potential:** While currently optimized for Windows (.exe), the logic is designed to be adaptable for mobile (.apk) environments.
* **Custom Masking:** The binary supports icon masking and custom .spec configurations for a personalized look and feel.

## 🚀 Getting Started

1. Download the `autoclicker.exe` from the repository.
2. Run the application (no administrative privileges required for basic operation).
3. Configure your click interval and trigger keys within the app interface.

## 📦 Requirements

Before running the AutoClicker, make sure you have the following installed:

- Python (3.8 or newer recommended)
- pip (Python package manager)

---

## 🐍 Install Python & pip

### 1. Download Python
- Go to: https://www.python.org/downloads/
- Download the latest version for Windows

### 2. Install Python
- Run the installer
- ✅ IMPORTANT: Check **"Add Python to PATH"**
- Click **Install Now**

### 3. Verify Installation

Open Command Prompt and run:

```bash
python --version
pip --version
```

If both show versions, you're good to go.

---

## 📚 Required Python Libraries

Install the required libraries using pip:

```bash
pip install pyautogui pynput
```

### Library Details
- `pyautogui` → Handles mouse automation
- `pynput` → Detects keyboard input for controls

---

## ▶️ How to Run the AutoClicker

### Option 1: Run the EXE
1. Download `autoclicker.exe`
2. Double-click to run
3. Follow on-screen instructions (if any)

### Option 2: Run via Python (if source is available)

```bash
python autoclicker.py
```

---

## 🛠 Tech Stack
* **Language:** Python
* **Environment:** Windows 11
* **Build Tools:** PyInstaller / Custom Spec files

## 📜 License & Disclaimer

### MIT License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### ⚠️ Disclaimer
> [!WARNING]
> This software is provided for educational and utility purposes only. Use this tool responsibly. The developer is not responsible for any bans, hardware wear, or damages resulting from the use of this software. Always check the terms of service of the applications you use this with.

## ⚠️ Important Note
> [!IMPORTANT]
> **Check this repository daily.** I am constantly pushing updates, performance tweaks, and new features. Make sure you are always running the latest version for the best response times and stability!

## ⚠️ Notes

- Some antivirus programs may flag AutoClickers as suspicious due to automation behavior.
- Run as Administrator if clicks are not registering in certain applications.
- Use responsibly — avoid violating software or game policies.

---
