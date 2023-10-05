[Simplified Chinese](README.md) | [Engilsh](READEME_EN.md)

## [Click to download the latest version](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/releases/latest)

# Announcement
As the LSPosed upstream has not been updated for a long time, it is not possible to complete the build properly, the build file source has been moved to https://github.com/YT-Advanced/MagiskOnWSALocal.git which has a maintenance

## ⚠️ Important Tips ⚠️ 

**If you don't read these tips, you and your family may be subjected to verbal abuse from me - this is disrespectful to the fruits of other people's labour**

Please do not Fork this repository, create one yourself and import the files.

Forking will cause the github action count of the repository you Forked to end up counting to the upstream repository and cause the upstream repository to be blocked, (that's how MagiskOnWSA got blocked)

## How it works

This project is based on a temporary clone of MagiskOnWSA and a direct call to build.sh to create the latest version and release it to Releases.

Click Watch - Custom - Publish New Version (Releases) to get an email notification when a new version is automatically built!

*Release attachments are built and uploaded by Github Action, feel free to review the [build.yml](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/edit/main/.github/workflows/Build) source code and suggest changes.

*As for any better way to publish, please feel free to suggest.

Default settings:

Run once a week at 12:00 UTC on Fridays, automatically run after modifying the workflow file, and skip the release if the version number already exists.

Official release version: build parameters: stable version stable; with root access (Magisk); with Google Play; remove Amazon store.

Pre-release version: build parameters: latest RP version; with root access (Magisk); with Google Play; remove Amazon store.

<details>
<summary><h2>How to build it yourself</h2></summary>
<p>Please don't Fork the repository directly, <a href="https://github.com/new/import">import the repository</a>yourself and fill in the following url <code>https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild</code></p>

After finishing, you need to open the file under /.github/workflows and change the preset value of Setup Parameters step to the upstream base repository and release repository you need.

Repository required private variable: [secrets.PUBLISH_TOKEN](https://github.com/settings/tokens) for accessing github and publishing, please give 'repo', 'read:org' permission.
</details>

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

Use the release and code of this project must comply with the [Anti-Labour Exploitation Permit](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/blob/main/Additional_LICENSE_CN)

## 星标

If this project has helped you, please give it a Star. This is an affirmation of my effortsヾ(≧▽≦*)o.

<p align="center">
  <a href="https://star-history.com/#yige-yigeren/MagiskOnWSAOnlineBuild&Date">
    <img src="https://api.star-history.com/svg?repos=yige-yigeren/MagiskOnWSAOnlineBuild&type=Date" alt="Star History Chart">
  </a>
</p>

## Utilities for Windows Subsystem for Android

**Tools created by other developers, just for suggestions*
        
[APK Installer On Microsoft Store](https://www.microsoft.com/store/productId/9P2JFQ43FPPG) [On Github](https://github.com/Paving-Base/APK-Installer) provides one-click APK installation, can bind APK file 
        
[WSA Toolbox On Microsoft Store](https://www.microsoft.com/store/productId/9PPSP2MKVTGT) [On Github](https://github.com/makazeu/WsaToolbox) APK installation, APP management, file transfer, QR code scanning 

---

**Copyright (C) 2023 Yige-Yigeren**

Android is a trademark of Google LLC. Windows is a trademark of Microsoft Corporation.

Translate By ChatGPT-4 && Google && DeeplL
