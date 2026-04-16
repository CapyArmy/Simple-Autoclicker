# AutoClicker

A high-performance, modern Windows utility designed for automated mouse clicking. Built on the Flutter engine via **Flet**, this application provides a sleek, card-based interface for streamlining repetitive tasks with a professional "Gemini-style" aesthetic.

## 🚀 Features

* **Precision Automation**: Fine-tune clicking intervals and frequencies with a responsive, high-speed backend.
* **Modern GUI**: A clean, Gemini-inspired user interface featuring native dark mode, smooth transitions, and intuitive controls.
* **Optimized & Portable**: Packaged as a single standalone executable using **Zstandard (zstd)** compression for a small footprint and fast startup.
* **Robust Core**: Powered by Python 3.x and modern libraries including OpenSSL (`libcrypto-3`, `libssl-3`) for stability.

## 🛠️ Technical Specifications

* **Binary Name**: `autoclicker.exe`
* **GUI Framework**: **Flet / Flutter**
* **Compression**: Zstandard
* **Platform**: Windows (x64)
* **Libraries Integrated**: 
    * `flet_core` & `flet_desktop`
    * `libcrypto-3.dll` & `libssl-3.dll`
    * `_zstd.pyd`

## 📋 Prerequisites

* **Operating System**: Windows 10 or Windows 11.
* **Permissions**: Running as an **Administrator** is recommended to ensure clicks register across all application types.

## ⚙️ How to Use

1.  **Download**: Locate the `autoclicker.exe` file in the main repository file list **under this README**.
2.  **Unblock**: Right-click the `.exe`, select **Properties**, check **Unblock**, and click **OK**.
3.  **Launch**: Double-click to open the modern dashboard.
4.  **Configure**: Use the sliders and inputs to set your click speed and mouse button preference.
5.  **Control**: Use the on-screen toggle or assigned hotkeys to start/stop the automation.

## 🔄 Stay Updated
**Keep checking this repository daily!** I am actively pushing updates, performance tweaks, and new features. To ensure you have the best experience and the latest security patches, make sure to visit this page every day to download the most recent version of the `.exe`.

## 🛠 Development & Build Instructions

To build the project from source:

1.  **Clone the Repository**:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO.git](https://github.com/YOUR_USERNAME/YOUR_REPO.git)
    ```
2.  **Install Requirements**:
    ```bash
    pip install flet pyinstaller zstandard
    ```
3.  **Build**:
    ```bash
    flet pack main.py --icon app_icon.ico
    ```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

## ⚠️ Disclaimer

This utility is intended for automation and accessibility. Users are responsible for ensuring compliance with the terms of service of any software or games. The developers are not liable for misuse or any consequences resulting from the use of this software.
