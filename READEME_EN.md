# [Click to download the latest version](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/releases/latest)

[简体中文](README.md) | [Engilsh](READEME_EN.md)

# ⚠️ Important Note ⚠️

**If you don't read these tips, you and your family may be abused by me - it's disrespectful to the fruits of other people's labor**

Please do not Fork this repository, create a repository yourself and import the files.

Fork will cause the github action count of your Fork warehouse to finally be counted to the upstream warehouse and cause the upstream warehouse to be banned (this is how MagiskOnWSA is blocked)

# How it works

This project is based on a temporary clone of MagiskOnWSA and uses build.sh directly to create and release the latest version.

Click Watch - Custom - Releases to receive email notifications after new versions are automatically built.

*Release attachments are all built and uploaded by Github Action, you are welcome to review the [build.yml](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/edit/main/.github/workflows/Build.yml) source code and suggest changes.

Default settings:

Runs once every Friday at 12:00 (UTC+0), and automatically runs after modifying the workflow file. If the version number already exists, the release will be skipped. (These options are disabled by default to prevent misuse)

Build parameters: Stable version; Root access (Magisk); With Google Play; Amazon store removed.

## If you want to build yourself

Please do not directly fork the repository. Instead, create your own repository and then add .github/workflows/Build.yml.

Because some people are indiscriminately forking this repository, all automatic activators are deactivated by default, please enable them yourself. The operation of releasing releases will be activated by an action in another private repository.

Required private variable: [secrets.PUBLISH_TOKEN](https://github.com/settings/tokens), for accessing GitHub and releasing, please grant 'repo', 'read:org' permissions.

Change the repository addresses to your own.

## Running

Fill in the parameters of build.sh in advance, skip run.sh and execute directly (if you need to modify parameters, please get them in run.sh), and publish using Github Releases.

If there is a better way to release, you can also suggest it.

## Disclaimer

This repository only automatically builds Magisk On for Android's Windows Subsystem in a public manner, it does not guarantee that the build is normal, the software can run normally, or the safety and reliability of your data.

Since MagiskOnWSA is still being updated, its build parameters may change, and this repository may not be able to change in time, please ensure that the corresponding parameters match your requirements before installing and using.

Not responsible for any data damage and loss caused by incorrect builds.

I will not collect any data and will provide the build as is.

*Currently, it is only released on Github Releases, do not download from other sources, the source files provided by other sources may contain malicious programs.

## Release Notes Link
        
[Release notes for the Windows Subsystem for Android](https://learn.microsoft.com/zh-cn/windows/android/wsa/release-notes)
        
[Detailed explanation of MagiskOnWSA](https://github.com/LSPosed/MagiskOnWSALocal#readme) (Read this article first before raising an Issue if you encounter installation problems and operation problems)
        
## Technical Support
        
This project does not provide any technical support for the Android subsystem. If the automatic build is abnormal or if you have any suggestions, please raise a [new Issue](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/issues/new) in this repository.
        
For 议题 related to Root access and Google Play running abnormally, please raise a [new Issue](https://github.com/LSPosed/MagiskOnWSALocal/issues/new/choose) in MagiskOnWSA.

For problems with the computer being unable to install the Android subsystem and running problems with the Android subsystem, please raise a question in the [Microsoft Community](https://answers.microsoft.com/zh-hans/newthread) (Choose Windows-Windows11-Applications-Amazon Appstore)

## About Copyright

MagiskOnWSALocal is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

The release and code of this project must comply with the [Anti Labor Oppression License](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/blob/main/Additional_LICENSE_CN)

## 星标

If this project has helped you, please give it a Star. This is an affirmation of my effortsヾ(≧▽≦*)o.

<p align="center">
  <a href="https://star-history.com/#yige-yigeren/MagiskOnWSAOnlineBuild&Date">
    <img src="https://api.star-history.com/svg?repos=yige-yigeren/MagiskOnWSAOnlineBuild&type=Date" alt="Star History Chart">
  </a>
</p>

## Utilities for Windows Subsystem for Android

**Tools created by other developers, just for suggestions*
        
[APK Installer On Microsoft Store](https://www.microsoft.com/store/productId/9P2JFQ43FPPG) provides one-click APK installation, can bind APK file
        
[WSA Toolbox On Microsoft Store](https://www.microsoft.com/store/productId/9PPSP2MKVTGT) APK installation, APP management, file transfer, QR code scanning

---

**Copyright (C) 2023 Yige-Yigeren**

Android is a trademark of Google LLC. Windows is a trademark of Microsoft Corporation.

Translate By ChatGPT-4
