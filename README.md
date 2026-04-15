# AutoClicker

A high-performance, lightweight Windows utility designed for automated mouse clicking. This application provides a professional graphical interface to configure and execute repetitive clicking tasks, helping to streamline workflows and reduce manual effort.

## 🚀 Features

* **Precision Automation**: Fine-tune clicking intervals to meet the requirements of specific software or gaming environments.
* **Modern Native GUI**: Built using the **Tkinter** framework, featuring a polished look using `vistaTheme` and `xpTheme` for seamless Windows integration.
* **Optimized & Fast**: Compiled with **Zstandard (zstd)** compression to ensure a small file size and rapid startup.
* **Portable Execution**: A standalone `.exe` that runs without needing Python installed on the host system.
* **Robust Backend**: Powered by Python 3.x and supported by industry-standard libraries like OpenSSL (`libcrypto-3` and `libssl-3`).

## 🛠️ Technical Specifications

* **Binary Name**: `autoclicker.exe`
* **Platform**: Windows (x86_64)
* **Core Engine**: Python 3
* **GUI Framework**: Tcl/Tk (Tkinter)
* **Packaging**: PyInstaller with `zstd` support
* **Dependencies Internalized**: 
    * `libcrypto-3.dll` & `libssl-3.dll`
    * `libffi-8.dll`
    * `_tkinter.pyd`

## 📋 Prerequisites

* **Operating System**: Windows 10 or Windows 11.
* **Permissions**: Depending on the target application, you may need to run the utility as an **Administrator** for clicks to register.

## ⚙️ How to Use

1.  **Download**: Locate the `autoclicker.exe` file provided in the file list **under the README** in this repository.
2.  **Unblock**: Right-click the `.exe`, select **Properties**, check **Unblock**, and click **OK** (required for some Windows security settings).
3.  **Launch**: Double-click the executable to open the interface.
4.  **Configure**: Set your desired click interval, button type (Left/Right), and repetition count.
5.  **Start/Stop**: Use the on-screen buttons or configured hotkeys to toggle the clicking action.

## 🛠 Development & Build Instructions

If you wish to build the binary from the source code:

1.  **Clone the Repository**:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO.git](https://github.com/YOUR_USERNAME/YOUR_REPO.git)
    ```
2.  **Install Requirements**:
    ```bash
    pip install pyinstaller zstandard
    ```
3.  **Build the Executable**:
    ```bash
    pyinstaller --onefile --windowed --noconsole main.py
    ```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

## ⚠️ Disclaimer

This utility is intended for automation and accessibility purposes. Users are responsible for ensuring that their use of an autoclicker complies with the terms of service of any third-party applications or games. The developers are not responsible for any misuse or consequences resulting from the use of this software.
