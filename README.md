# AutoClicker

A lightweight Windows utility designed for automated mouse clicking tasks. This application provides a simple graphical interface to configure and execute clicks efficiently.



## Features

* **User-Friendly Interface**: Built with a clean GUI using the **Tkinter** framework for easy navigation.
* **Customizable Intervals**: Allows for precise control over clicking frequency.
* **Portable Executable**: Runs as a standalone `.exe` file on Windows—no Python installation required.
* **Theme Support**: Utilizes native Windows themes (Vista/XP) for a consistent look and feel.

## Technical Specifications

The application is built using Python and compiled into a Windows binary. Key technical components include:

* **Language**: Python 3
* **GUI Framework**: Tkinter / Tcl/Tk
* **Compilation Tool**: PyInstaller (packaged with `zstd` compression)
* **Dependencies**: 
    * `libcrypto-3.dll` & `libssl-3.dll` for secure operations.
    * `_tkinter.pyd` for the graphical backend.
    * `base_library.zip` containing essential Python modules.

## Installation & Usage

1.  Navigate to the **Releases** section of this repository.
2.  Download the latest `autoclicker.exe`.
3.  Double-click the file to launch the application.
4.  Configure your clicking parameters and press **Start**.

## Development

If you wish to modify the source code:
1.  Ensure you have **Python 3.x** installed.
2.  Install required dependencies via pip (if applicable).
3.  To compile your own executable, use PyInstaller:
    ```bash
    pyinstaller --onefile --noconsole main.py
    ```

## Disclaimer

This software is for automation and educational purposes. Please ensure your use of this tool complies with the terms of service of any third-party software or games.
