## Wineskin Unofficial Update
A working version of Wineskin using the development code from [Wineskin](https://github.com/vitor251093/wineskin) with some tweaks, the [Original Wineskin Code](https://sourceforge.net/p/wineskin/code) was updated by [VitorMM](https://github.com/vitor251093) and some additional features and fixes by myself [Unoffical_Wineskin](https://github.com/vitor251093/wineskin/tree/Unoffical_Wineskin).
Unlike the [Official Wineskin Project](http://wineskin.urgesoftware.com) by doh123 that worked on *macOSX10.6*, this project is only supported on *MacOSX10.8* to *macOS10.14*

## About macOS Catalina support;
*WS11WineCX19.0.1* & *WS11WineCX64Bit19.0.1* include wine32on64 and can function on macOS Catalina but these have not been signed or notarized so to make use of these you need to disable SIP in order for wine32on64 to set the kernal flag to allow 32Bit code execution.

## Contained here;
1) Wine versions packaged as *Engines* to be used with "Wineskin Winery"
2) WineskinWinery.app - *The current version will be downloaded updating the local version*
3) Wineskin Unoffical Update's - *Master Wrapper*

## Currently available compiled Wine Versions (Engines)
- WS11WineCX64Bit19.0.1
- WS11WineCX19.0.1
- WS10WineCX64Bit18.5.0
- WS10WineCX18.5.0

*All other Wine versions are repacked from [Winehq](https://dl.winehq.org/wine-builds/macosx/pool/) into Engines*

## Issues with custom engines!
Custom Engines are now cross-compiled however they still currently have the following [issues](https://wiki.winehq.org/Clang) that means some features will not work like official versions from WineHQ.

## SSL errors!?
- OSX 10.8 will get SSL errors due to only supporting TLS1.0
- OSX 10.9 supports TLS1.2 and that's the required minimum requirement for secure websites and online game platforms like Steam.

## License
Keeping the same as the original material, LGPL 2.1 is the license of that project. You can find more details about that in the LICENSE file.

## Credits
- [VitorMM](https://github.com/vitor251093) for modernizing the [Wineskin Codebase](https://github.com/vitor251093/wineskin) & [ObjectiveC_Extension](https://github.com/vitor251093/ObjectiveC_Extension)
- Special thanks to doh123, for creating [Wineskin](http://wineskin.urgesoftware.com).
