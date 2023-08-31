[简体中文](README.md) | [Engilsh](READEME_EN.md)

## [点击下载最新版本](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/releases/latest)

# ⚠️重要提示⚠️ 

**如果你不阅读这些提示，你和你的家人可能受到我的辱骂——这是对他人劳动成果的不尊重**

请不要Fork这个仓库，自己创建一个仓库并导入文件。

Fork会导致你Fork的仓库的github action计数最终统计到上游仓库并导致上游仓库被封禁，（MagiskOnWSA就是这么被封的）

## 工作原理

本项目基于临时克隆MagiskOnWSA，并直接调用build.sh来创建最新版本并发布于Releases。

点击关注（Watch） - 自定义（Custom） - 发布新版本（Releases），以在自动构建新版本后获取邮件通知

*发布附件均由Github Action构建并上传，欢迎审阅[build.yml](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/edit/main/.github/workflows/Build.yml)源码并提出修改意见。

*至于有什么更好的发布的方法也可以，也欢迎提出建议。

默认设置：

每周五12点（UTC+0）运行一次，修改workflow文件后自动运行，如果版本号已存在则跳过发布。

正式发布版：build参数：稳定版stable；有root权限(Magisk)；带Google Play；移除Amazon store。

预发布版：build参数：最新版RP；有root权限(Magisk)；带Google Play；移除Amazon store。

<details>
<summary><h2>如何自己构建</h2></summary>
<p>请不要直接Fork仓库，自己<a href="https://github.com/new/import">创建仓库</a>，并填入以下网址<code>https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild</code></p>

在完成后，需要打开/.github/workflows下的文件并修改Setup Parameters步骤的预设值为你需要的上游基础仓库和发布仓库。

仓库必需私有变量：[secrets.PUBLISH_TOKEN](https://github.com/settings/tokens)，用于访问github并发布，请给予'repo', 'read:org'权限。
</details>

## 免责声明

本仓库仅以公开的方式自动构建Magisk On 适用于 Android™️ 的 Windows 子系统，不提供对于构建正常、软件能正常运行的保证，不保证您数据的安全性与可靠性。

由于MagiskOnWSA仍然处于更新中，其Build参数可能会变化，本仓库不一定能及时更改，请在安装使用前确保相应参数与你的要求相匹配。
        
不对错误的Build造成的数据损坏与丢失负任何责任。
        
我不会收集任何数据，仅以原样提供构建。

*当前仅发布在Github Releases，请勿从其他来源下载，其他来源提供的源文件可能包含恶意程序。

## 发行说明链接
        
[适用于 Android 的 Windows 子系统发行说明](https://learn.microsoft.com/zh-cn/windows/android/wsa/release-notes)
        
[MagiskOnWSA的详细说明](https://github.com/LSPosed/MagiskOnWSALocal#readme) （出现安装问题与运行问题先阅读本文再提Issue）
        
## 技术支持
        
本项目不提供关于安卓子系统的任何技术支持，如果自动构建不正常或者有什么建议，在本仓库请提出一个[新的Issue](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/issues/new)。
        
关于Root权限及Google Play运行异常的问题请在MagiskOnWSA提出一个[新的Issue](https://github.com/LSPosed/MagiskOnWSALocal/issues/new/choose)。

关于电脑无法安装安卓子系统和安卓子系统运行问题，请在[微软社区](https://answers.microsoft.com/zh-hans/newthread)提出一个问题（选择Windows-Windows11-应用程序-Amazon Appstore）

## 关于版权

MagiskOnWSALocal is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

使用本项目发布的release与代码需遵守[反劳动压迫许可证](https://github.com/yige-yigeren/MagiskOnWSAOnlineBuild/blob/main/Additional_LICENSE_CN)

## 星标

如果这个项目有帮到你，请点个Star，这是对我努力的肯定ヾ(≧▽≦*)o。

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yige-yigeren/MagiskOnWSAOnlineBuild&type=Date)](https://star-history.com/#yige-yigeren/MagiskOnWSAOnlineBuild&Date)

## 适用于 Android 的 Windows 子系统实用工具
        
**其他开发者创建的工具，仅作建议*
        
[APK安装程序 On Microsoft Store](https://www.microsoft.com/store/productId/9P2JFQ43FPPG) [On Github](https://github.com/Paving-Base/APK-Installer) 提供一键式APK安装，可绑定APK文件
        
[WSA工具箱 On Microsoft Store](https://www.microsoft.com/store/productId/9PPSP2MKVTGT) [On Github](https://github.com/makazeu/WsaToolbox) APK安装，APP管理，文件传输，扫描二维码

---

**Copyright (C) 2023 Yige-Yigeren**

Android is a trademark of Google LLC. Windows is a trademark of Microsoft Corporation.
