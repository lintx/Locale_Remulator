# Locale Remulator

[![license](https://img.shields.io/github/license/InWILL/Locale_Remulator.svg)](https://www.gnu.org/licenses/lgpl-3.0.en.html)

类似于Locale Emulator，但是没有64位，所以基于MinHook重新实现了一个，外围部分参照了LE的代码。

最主要的原因是日服MapleStory要实装64位了。

wiki在做了在做了（咕咕咕······

System Region and Language Simulator.

The project is similar with Locale-Emulator, but LE doesn't support 64-bit application, so I base on Minhook to start a new project.

The most important reason is that Japan MapleStory will become 64-bit.

## Getting Started

### Prerequisites

* [.NET Framework Runtime 4.7.2 or higher](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net472)

## Install

Run `register.bat` to register right-click menu.

## Uninstall

Run `unregister.bat` to remove right-click menu.

## Usage

Select a `*.exe` application and right click, there will show a section named "Locale Remulator x64", and choose what config you want.

## Built With

* [MinHook](https://github.com/TsudaKageyu/minhook) - Used to hook unicode function
* [SharpShell](https://github.com/dwmkerr/sharpshell) - Used to generate right-click menu

## License

This project is licensed under the LGPL-3.0 License - see the [LICENSE](LICENSE) file for details
