# 【mpv-lazy】功能强大的 mpv 懒人版

⚠️ **本文不再更新，建议使用 [mpv.net_CM](https://kutt.lckp.top/uVaT3U)** ⚠️

原文链接：[https://kutt.lckp.top/OoKfyb](https://kutt.lckp.top/OoKfyb)

视频链接：[https://kutt.lckp.top/zgTyBs](https://kutt.lckp.top/zgTyBs)

## 1. ⬇️ 下载

奶牛快传：[https://kutt.lckp.top/E3fbwv](https://kutt.lckp.top/E3fbwv)

## 2. 🔩 安装

解压到想要安装的路径

🔥 **注意：安装路径不要包含中文和空格等特殊字符，并且建议不要使用 C 盘**

![20230211061922](https://github.lckp.top/LuckyPuppy514/blog/main/mpv-lazy/图片/20230211061922.jpg)

右键以管理员身份运行 installer/mpv-install.bat

![20230211062155](https://github.lckp.top/LuckyPuppy514/blog/main/mpv-lazy/图片/20230211062155.jpg)

## 3. ⚙️ 设置

配置文件路径：`portable_config/mpv.conf`

### 3.1. 独显运行（单显卡可不设置）

找到 `d3d11-adapter` 和 `vulkan-device` 所在行，删除 `#` 号，并修改显卡名称

![20230211063351](https://github.lckp.top/LuckyPuppy514/blog/main/mpv-lazy/图片/20230211063351.jpg)

### 3.2. 性能相关（卡顿可尝试修改）

硬解模式（N卡建议 `nvdec-copy`，其他建议默认）

```text
hwdec = auto-copy
```

音视频同步模式（卡顿可用 # 注释掉）

```text
# video-sync = display-resample
```

视频缓冲大小（高分辨率可适当调大）

```text
demuxer-max-bytes = 200MiB
```

补帧（卡顿请切换模式，或用 # 注释掉）

```text
# vf-append = vapoursynth = "~~/vs/mvtools-2x.vpy"
```

## 4. ⌨️ 快捷键

快捷键配置文件路径：`portable_config/input.conf`

| 功能 | 快捷键 | 备注 |
|:-------:|:-------:|:-------:|
| 开启着色器 | ctrl + 1-9 | 动漫建议 1-6 |
| 清空着色器 | ctrl + 0 | - |
| 开启/关闭补帧 | shift + 1-5 | 切换时请先关闭当前方案，否则容易卡顿 |
| 色彩调节 | 数字键 0-9 | - |
| 音量 | - = | - |
| 快进快退 | 方向键 | 左右 10s，上下 60s |
| 全屏 | 回车键 | - |
| 退出全屏 | esc | - |
| 暂停 | 空格 | - |

## 5. 🌟 在线播放插件

安装教程：[https://kutt.lckp.top/lPFDM7](https://kutt.lckp.top/lPFDM7)

支持网站：[https://kutt.lckp.top/CfCIIc](https://kutt.lckp.top/CfCIIc)

![20230210223220](https://github.lckp.top/LuckyPuppy514/blog/main/mpv.net_CM/图片/20230210223220.jpg)

## 6. 👏 特别感谢

- [https://github.com/hooke007/MPV_lazy](https://github.com/hooke007/MPV_lazy)
