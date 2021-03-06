<div align=center><img src="https://raw.githubusercontent.com/geeetech3d/smartto/master/docs/assets/smartto-logo.png" width="400" height="100" alt="smartto-logo" /></div>

## Status
[![Opensource](https://img.shields.io/badge/Opensource%20by-Geeetech3D-blue.svg)](https://www.geeetech.com/)
[![Join the chat at https://gitter.im/geeetech3d/Smartto](https://badges.gitter.im/geeetech3d/Smartto.svg)](https://gitter.im/geeetech3d/Smartto?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Introduction
3D printer firmware and hardware for stm32

## What's included
Folder | Description
--- | ---
firmwares | source code of this project(including IAR version and Eclipse version)
circuit_diagram | electronic circuit diagrams of A30 / E180 / 301 
tools | mini scripts for using firmwares or controlling motor

## Support
Company | Production
--- | ---
Geeetech | A30 / E180 / 301

## Platform--IAR(stable)

## Platform--Eclipse(alpha)

### How to compile STM32
Step 1: Install Java environment

You can download JDK from [here (32bits)](http://www.geeetech.com/OpenSource/eclipse/chromeinstall-8u171.exe) or Java official website

Step 2: Download and unzip project source code and toolchain

File | Download
--- | ---
Toolchain | [Geeetech](http://www.geeetech.com/OpenSource/eclipse/arm-none-eabi-gcc-8.1.0-180502-win32.7z)
Eclipse | [Geeetech](http://www.geeetech.com/OpenSource/eclipse/gnumcueclipse4.3.2-oxygen-win32x86.zip)
Project | STM32f103r.zip

Step3: Import the project into Eclipse

[Eclipse Tools](http://www.geeetech.com/OpenSource/)

## Smartto Tool

You can get stable and legacy versions of firmware from [here](http://geeetech.com/firmware/) and [here](https://github.com/Geeetech3D/Smartto/tree/master/firmwares/logs/firmware_changelog.md) for changelog. We will put compiled firmware which is latest version but not be tested into firmwares/test/

### Platform--Windows
<div align=center><img src="https://raw.githubusercontent.com/geeetech3d/smartto/master/docs/assets/motor_tool_snapshot.png" width="400" height="400" alt="motor-tool-usage" /></div>

### Platform--Mac
<div align=center><img src="https://raw.githubusercontent.com/geeetech3d/smartto/master/docs/assets/motor_tool_mac_snapshot.png" width="400" height="400" alt="motor-tool-mac-usage" /></div>

## Changelog

2018/7/5 Add M201-M205 support in motor tool V1.0 

## License
GPL v2
