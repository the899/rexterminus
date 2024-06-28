# macOS 上使用 Electron 客户端

## 先安装 mpv

bash

```
brew install mpv
```

## 安装 Emby Electron Premiere 破解版

下载安装 Emby Electron Premiere 破解版：[点击下载](https://github.com/rartv/EmbyPublic/releases/download/0.0.1/Emby.Theater-3.0.12.dmg)

此客户端由群里大佬自行 [编译](https://github.com/MediaBrowser/emby-theater-electron) 并破解

## 设置外部播放器 [ 可选 ]

1. 安装 [IINA 播放器](https://www.iina.io/)
2. 打开 Emby Theater 的 **设置** -> **External Players**，点击 **添加**，**播放器路径** 填写 `/Applications/IINA.app/Contents/MacOS/iina-cli`，把 **视频文件** 和 **网络流** 勾上，命令行参数填写

bash

```
{path}
--mpv-start={Seconds}
```

注意每行一条参数，然后点 **存储**