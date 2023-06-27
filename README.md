# [点击下载最新版本](https://github.com/yige-yigeren/MagiskOnWSAAuto/releases/latest)

本项目基于临时克隆MagiskOnWSA，并直接调用build.sh来创建最新版本。

默认参数：

每两周运行一次。

稳定通道；root Magisk；Google Play；去除亚马逊商店。

请不要直接fork仓库，自己创建仓库后将Build.yml填入即可。

必需私有变量：[PUBLISH_TOKEN](https://github.com/settings/tokens)，用于访问github并发布，请给予仓库相关权限。

运行原理：提前预填好build.sh的参数，跳过run.sh直接执行（需要修改参数请run.sh里获取），使用Github Releases发布。

至于为什么使用独立压缩，一是原版好像有bug怎么选都是7z，zip比7z也大不到哪去，第二zip方便小白解压（我这个项目就是给不会部署WSL的小白的）。

<p align="center">
  <a href="https://star-history.com/#yige-yigeren//MagiskOnWSAAuto&Date">
    <img src="https://api.star-history.com/svg?repos=yige-yigeren/MagiskOnWSAAuto&type=Date" alt="Star History Chart">
  </a>
</p>
