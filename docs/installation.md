# Installation
This guide shows how to install AndroidIDE, setting up the terminal and the Android build tools installation.

Before getting started, please make sure that your Android device meets the minimum requirements.

## Minimum requirements
- ARM based CPU `arm64-v8a` (a.k.a aarch64) or `armeabi-v7a`.
- At least 1.5GB of RAM **_available for use_** (not total RAM).
- At least 4GB of free space is recommended. Around 1.5GB for installation and rest for other dependencies that you might need to download depending on your project.

## Setup the terminal [^cheat]
- Open AndroidIDE [terminal](./user_interface#terminal). It will install the bootstrap packages.
- Then run `pkg upgrade` to update packages to latest version.

## Build Tools Installation [^cheat]
Install the JDK, SDK and commandline tools for sdk.

- Open terminal and run `idesetup -c`.
- After you execute the above command, it'll show a summary of the configuration. Type `y` to confirm the configuration and start the installation process.
- After successful installation, `Downloads completed. You are ready to go!` will be printed.

You can execute `idesetup -h` to see configuration options.

[^cheat]:
    Cheatsheet : 
    - One command to setup the terminal and to install build tools.
        ```bash
        cd && pkg upg && idesetup -c
        ```
#中文字幕
#安装
本指南介绍如何安装AndroidIDE、设置终端和Android构建工具安装。
开始之前，请确保您的Android设备满足最低要求。
##最低要求
-基于ARM的CPU“arm64-v8a”（又名aarch64）或“armeabi-v7a”。
-至少1.5GB的RAM**_可供使用_**（非总RAM）。
-建议至少有4GB的可用空间。大约1.5GB用于安装，其余用于您可能需要下载的其他依赖项，具体取决于您的项目。
##设置终端[^欺骗]
-打开AndroidIDE[terminal]（./user_interface#terminal）。它将安装引导程序包。
-然后运行“pkg升级”将软件包更新到最新版本。
##生成工具安装[^cheat]
为SDK安装JDK、SDK和命令行工具。
-打开终端并运行“idesetup-c”。
-执行上述命令后，它将显示配置的摘要。键入“y”以确认配置并开始安装过程。
-成功安装后，`下载完成。你准备好了！”将打印。
您可以执行“idesetup-h”以查看配置选项。
[^欺骗]：
收费表：
-一个命令用于设置终端和安装构建工具。
```猛击
cd&&pkg upg&&idesetup-c
```
