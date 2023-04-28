# 【mpv-lazy】强大的 mpv 懒人版

![20230219195746](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219195746.webp)

功能强大的 mpv 懒人版，已集成 anime4k 和多种着色器，以及各种补帧滤镜和脚本，可实时提升动漫画质和帧数<!--more-->

- 博客原文：[https://kutt.lckp.top/OoKfyb](https://kutt.lckp.top/OoKfyb)
- 视频教程：[https://kutt.lckp.top/zgTyBs](https://kutt.lckp.top/zgTyBs)

⚠️ 本文不再更新，建议使用 `mpv.net_CM`，具备同等功能，且安装和使用都更为方便

- `mpv.net_CM`：[https://kutt.lckp.top/uVaT3U](https://kutt.lckp.top/uVaT3U)

## 1. ⬇️ 下载

- 地址：[https://kutt.lckp.top/E3fbwv](https://kutt.lckp.top/E3fbwv)
- 密码：`1b8r`

## 2. 🧭 安装

鼠标右键解压到想要安装的路径，右键以管理员身份运行 installer/mpv-install.bat 即可

🔥 安装路径 **不要包含中文**，C 盘建议放在当前用户目录下

![20230219201908](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219201908.webp)

## 3. ⚙️ 设置

配置文件路径：`portable_config/mpv.conf`（可用记事本打开）

### 3.1. 独显运行（单显卡可不设置）

找到 `d3d11-adapter` 和 `vulkan-device` 所在行，删除 `#` 号，修改显卡名称后保存

![20230219202207](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219202207.webp)

显卡名称可在设备管理器中找到

![20230219202352](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-19/20230219202352.webp)

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

![20230215110805](https://image.lckp.top/LuckyPuppy514/image/raw/main/screenshot/2023/2023-02-15/20230215110805.webp)

## 6. 🤔 问题反馈

- [https://kutt.lckp.top/J4wW78](https://kutt.lckp.top/J4wW78)

## 7. 👏 特别感谢

- [https://github.com/hooke007/MPV_lazy](https://github.com/hooke007/MPV_lazy)
