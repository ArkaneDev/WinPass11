# WinPass11: Guided Installer

**Join us on Discord**: https://discord.gg/bD2TMR8t29

🔑 [WinPass11](https://github.com/project-winpass11) Guided Installer is a tool for installing Windows 11 on unsupported hardware through a walkthrough process. Our goal is for the end-user to easily run a single executable and have access to Windows 11 through the dev channel with no worries about your unsupported hardware. This program will support bypassing unsupported processors, the TPM 2.0 requirement, the secure boot check and hopefully more!

## Prerequisites
* [Microsoft .NET Core 3.1](https://dotnet.microsoft.com/download/dotnet/3.1) (It's recommended to install this version alongside your current .NET version because we don't know for sure if other versions work)

## Installation
* Download the [latest release](https://github.com/project-winpass11/WinPass11.GuidedInstaller/releases).
* Unzip the `{Version}_Release.zip` or `{Version}_Debug.zip` archives in file in file explorer. (This depends if you want debug points or not)
* Execute the program named: `WinPass11.GuidedInstall.exe` as administrator. (You should be asked by UAC to elevate permission)

## Contributing
When your machine is ready for development, take a look at CONTRIBUTING.md to see how to get your changes merged in.

## License
WinPass11.WinService is licensed by project-winpass11 under the Apache License. (see LICENSE). The usage of third-party packages and programs is determined by the terms of their individual licenses.


## Old repo

If for whatever reason you require the code for an older version, the code for that was accidentally overriten during a cleanup but was replaced [here](https://github.com/project-winpass11/guided-installer-precleanup)
