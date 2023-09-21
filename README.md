# STM32 firmware development with Visual Studio Code 
Guide for developing embedded systems in the Visual Studio Code for ST Microelectronics STM32 devices.

## Overview
This project provides development of embedded systems in the Visual Studio Code IDE. With the help of some extensions compiling, flashing, debugging and tracing is made possible. GNU Make is used as build system. 

## Installation:
- [STM32CubeCLT](https://www.st.com/en/development-tools/stm32cubeclt.html) (Includes GNU C/C++ for Arm® toolchain, GDB debugger client and server, STM32CubeProgrammer CLI, System view descriptor files)
- [GNU Make](https://www.gnu.org/software/make/) (Easiest way for installing GNU Make on Windows is via [Chocolate](https://chocolatey.org/install) or MinGW )
- [Visual Studio Code](https://code.visualstudio.com/download) with following extensions:
  - [Corte-Debug](https://github.com/Marus/cortex-debug) (Provides debugging support for ARM Cortex-M Microcontrollers)
  - [C/C++ Extension](https://github.com/Microsoft/vscode-cpptools) (The C/C++ extension adds language support for C/C++ to Visual Studio Code, including editing (IntelliSense) and debugging features)
  - Recommended: [Task Runner](https://github.com/sana-ajani/taskrunner-code) VS Code extension to view and run tasks from Explorer panel
  - Recommended: [Serial Monitor](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-serial-monitor) VS Code Extension for sendinig and receiving messages from serial ports. (Useful if *printf* messages are redirected to a virtual COM port)



